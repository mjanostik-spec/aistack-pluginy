# Stavba paměti: jak roste a nezarůstá

Prahy jsou orientační. Když je důvod udělat změnu dřív nebo později, navrhni to.

Každou změnu stavby navrhni jednou větou a proveď až po souhlasu. Při týdenním ohlédnutí je nabídni najednou jako krátký seznam. Po každé změně oprav `REJSTRIK.md`.

## Nové typy dokumentů

Paměť začíná se vzory ve `vzory\`: práce, postup, člověk nebo firma, plán, větev. Práce každého člověka je jiná, takže typy přibývají.

- Když obsah **podruhé** nesedí do žádného vzoru (reklamace, výběrové řízení, zápis z porady, klient, zakázka), navrhni nový typ: jak se jmenuje, kdy se použije, jaké má oddíly.
- Po souhlasu ulož vzor do `vzory\<typ>.md`, založ pro typ složku (`reklamace\`) a obě dosavadní stránky do ní převeď.
- Při prvním výskytu nový typ nezakládej. Použij nejbližší vzor a poznamenej si to do deníku.
- Vzor má nejvýš šest oddílů. Když uživatel některý oddíl třikrát nechá prázdný, navrhni ho ze vzoru vyřadit.

## Atomizace

Jedna stránka, jedna věc.

- Stránku nad 150 řádků nebo se dvěma samostatnými tématy rozděl.
- Na původním místě nech shrnutí na pár řádků a odkazy na nové stránky. Adresa stránky se nemění, takže staré odkazy platí.
- Seznamové soubory (`lide.md`, `slovnik.md`, `rozhodnuti.md`) děl podle přirozené hranice: firma, oblast, rok.

## Archivace

- Dokončenou práci přesuň do `archiv\RRRR\`. V `REJSTRIK.md` po ní nech jeden řádek s výsledkem a cestou. Z `PREHLED.md` ji odstraň.
- Uzavřené otázky a vlákna starší než čtvrt roku přesuň do `archiv\RRRR\`.
- Nic nemaž. Archiv čti jen na vyžádání nebo když na něj vede odkaz.
- Práce, na kterou se dva měsíce nesáhlo, není hotová. Zeptej se, jestli je odložená, zrušená, nebo hotová.

## Plán větší práce

Když práce zabere víc než jedno sezení nebo má víc než pět kroků, navrhni jí vlastní složku `prace\<nazev>\` se souborem `plan.md` podle vzoru `vzory\plan.md`:

- cíl jednou větou,
- podle čeho poznáme, že je hotovo,
- kroky se stavem (`[ ]` čeká, `[~]` rozdělané, `[x]` hotovo, `[-]` zrušeno),
- další krok: co přesně udělat příště,
- rozhodnutí a otevřené otázky této práce (odkazem do `rozhodnuti.md` a `otazky.md`),
- soubory na disku, kterých se práce týká.

Každé sezení na té práci začni přečtením plánu a řekni jednou větou, kde jste skončili. Plán opravuj průběžně, hlavně „další krok“. Podstránky práce patří do stejné složky.

## Větev pro velkou složku

Složka s víc než třiceti dokumenty dostane vlastní větev `vetve\<nazev>\`:

- `INDEX.md`: k čemu složka je, jak je uspořádaná, jeden řádek o každém dokumentu nebo skupině dokumentů, který už znáš (název, co v něm je, datum souboru),
- stránky pro to podstatné, co se z dokumentů používá opakovaně.

V `mapa-slozek.md` zůstane o složce jediný řádek s odkazem na větev.

- Větev stav postupně, jak dokumenty při práci opravdu čteš. Nečti kvůli ní celou složku najednou, pokud o to uživatel nepožádá.
- Do větve patří výtahy a odkazy na soubory, nikdy kopie dokumentů.
- U každého výtahu uveď cestu a datum souboru. Když je soubor na disku novější než výtah, výtah je podezřelý: přečti soubor znovu.
- Když podsložka sama přeroste třicet dokumentů nebo `INDEX.md` 150 řádků, založ pod větví další větev stejným způsobem (`vetve\<nazev>\<podslozka>\INDEX.md`).

## Postup a vlastní skill

- Když deník ukáže, že se stejná věc dělá potřetí, nabídni sepsat postup do `postupy\`.
- Postup použitý pětkrát nabídni převést na vlastní skill uživatele (v aplikaci Customize, Skills) nebo na plánovanou úlohu. Vysvětli jednou větou, co tím získá.
