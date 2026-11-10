# Změny pluginu Mozek

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
