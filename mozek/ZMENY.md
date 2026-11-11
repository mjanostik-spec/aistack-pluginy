# Změny pluginu Mozek

## 1.1.0 (2026-11-11)

Cíl: víc užitku a méně vyrušování. Podle druhé zkoušky s deseti fiktivními uživateli.

- **Nejdřív práce, potom nastavování.** Úvod má tři věty a jednu otázku: co pro vás mám udělat jako první. Vložení pokynů do projektu přijde až po první hotové věci, jako jediný úkol na půl minuty.
- **Stavbu paměti si Claude řídí sám.** Na plán práce, přehled velké složky, rozdělení poznámek a archivaci se už neptá. Ptá se jen na to, co se týká vás: postup nebo skill, poznámky ve vaší sdílené složce, smazání.
- **Nejvýš jedna věc navíc k odpovědi a dvě za celý rozhovor.** Jedno pořadí pro všechno: termín, otázka, srovnání s návrhy, tip.
- **Ohlédnutí a zastavení s učitelem se nabízejí jako jedna věc** na pět minut, ne dvě po sobě. Ohlédnutí má nejvýš tři otázky a úklid dělá Claude sám.
- **První týden žádné tipy,** potom nejvýš dva týdně. Po „ne“ už se Claude neptá, jestli má zastavení vypnout.
- **Claude ukáže, že navazuje:** na začátku jednou větou řekne, na co navazuje a která vaše pravidla drží.
- **Odhadne, místo aby se ptal.** Chybějící údaj, který jde odvodit z dřívější práce, použije jako označený odhad a práci dokončí.
- **Hlídá za vás:** rozpory mezi dokumenty, čísla, která nesedí, a lhůty řekne u výsledku. Čísla ve svém výstupu ověřuje sám.
- **Vzdálené termíny:** neslibuje, že se ozve. Nabídne připomínku do kalendáře.
- **Do starých rozhovorů vás posílá jen výjimečně.** Odpovídá z paměti; co nezaznělo, řekne rovnou.
- **Výstupy pro poslání dál a na mobil jako PDF nebo Word,** ne HTML. Krátké návrhy ukládá do souboru, ať se nehledají v rozhovoru.
- **Průzkum složky:** odmítnutí celého disku rovnou nabídne, kterou složku projít.
- **Přesnější paměť:** co navrhl Claude a vy jste přijali, je v paměti odlišené od toho, co jste řekli. Nejistá odpověď otázku neuzavře. Pravidlo jedné zakázky se nestane obecným.
- **Citlivé údaje:** tři různé reakce podle situace místo jedné strojové věty; upozornění na zpracování jednou, před prvním čtením.

## 1.0.0 (2026-11-11)

První vydaná verze. Proti zkušební 0.1.0 se změnilo podle zkoušky s deseti fiktivními uživateli:

- **Kratší začátek.** Úvodní rozhovor má tři otázky místo šesti a první hotovou věc dostanete do deseti minut. Na začátku zazní, co je projekt a co složka mozku.
- **Méně vyrušování.** Po dokončené práci přidá Claude k výsledku nejvýš jednu věc navíc (otázku, návrh, nebo tip). Když řeknete „teď ne“, v tom rozhovoru se už neptá. O přejmenování rozhovoru nežádá.
- **Zápis před odpovědí.** Co má zůstat v paměti, zapíše Claude dřív, než odešle výsledek, takže zavřené okno nic neztratí.
- **Přesnější paměť.** Co jste řekli, co je v souboru, co Claude spočítal a co jen odhaduje, je v paměti odlišené. Pokyn k jedné věci se nestane obecným pravidlem.
- **Termíny.** Cokoli s datem jde rovnou mezi termíny. Na začátku práce Claude zmíní, co se blíží, a zeptá se na to, co prošlo a neví, jak dopadlo.
- **Citlivé údaje.** Soubory, které vypadají citlivě, Claude neotvírá bez potřeby a předem to řekne. Pravidla platí i pro údaje o jiných lidech. Smazání z paměti je úplné a nezanechá poznámku o smazání.
- **Učitel.** Nezapisuje si, co neumíte, jen co jste udělali. Zastavení nabídne nejvýš jednou denně a po dvojím odložení se zeptá, jestli ho má vypnout. „Tipy nechci“ platí i pro nabídky postupů.
- **Nové: průzkum složky** příkazem `/mozek:pruzkum`, s pojistkami proti procházení celého disku.
- **Nové: paměť přímo ve složce klienta nebo projektu** (místní větev), když si o ni řeknete.
- **Nové: nabídka ohlédnutí,** když od posledního uplynulo víc než deset dní.
- Příkaz `/mozek:ucitel` se jmenuje `/mozek:zastaveni`.

## 0.1.0 (2026-11-10)

Zkušební verze: paměť ve složce textových souborů, otázky, index rozhovorů, učitel s čtrnáctidenním kolem.
