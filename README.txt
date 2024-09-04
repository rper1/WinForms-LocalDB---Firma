

Zaměstnanci - aplikace s WinForms a databází

Umožňuje přidávat osoby do DB, odstraňovat je z ní a obnovit původní seznam osob ze záložní DB,
kterou nelze uživatelsky upravovat.

Program správně funguje (Nahled.png), pokud je nainstalována SQL Server Express 2019 LocalDB, která je jako jediná LocalDB součástí Visual Studia Community 2022 a v případě její absence ji lze doinstalovat např. v oddílech "Vývoj desktopových aplikací pomocí .NET" nebo "Ukládání a zpracování dat".


při přidávání osoby
- kontroluje vyplnění polí, upozorní na nedostatek
- odstraňuje zadané mezery, oddělení nelze ručně zapsat ani editovat
- dynamicky mění červený chybový text ihned po každé změně v zadávacích polích
