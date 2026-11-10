# Stavba paměti: jak roste a nezarůstá

Prahy jsou orientační. Když je důvod udělat změnu dřív nebo později, navrhni to.

**Souhlas.** Každou změnu stavby navrhni jednou větou, která říká, co uživatel získá, a proveď ji až po výslovném „ano“. Návrh bez odpovědi zapiš do `PREHLED.md` pod „Čeká na souhlas“. Návrh stavby se počítá jako „jedna věc navíc“ po dokončené práci. Při ohlédnutí nabídni návrhy najednou jako krátký seznam. Po každé změně oprav `REJSTRIK.md` a odkazy, které na změněné stránky vedou.

**Hlasitost.** Nabídka plánu, postupu, větve nebo skillu je návrh jako tip. Když má uživatel v `ucitel.md` tipy vypnuté nebo si návrhy omezil v `jak-pracuju.md`, nenabízej je při práci; poznamenej si je a nabídni při ohlédnutí, o které si sám řekne.

## Nové typy dokumentů

Vzory jsou v `assets/vzory/` tohoto skillu: práce, postup, člověk nebo firma, plán, větev. Práce každého člověka je jiná, takže typy přibývají.

- „Nesedí do vzoru“ znamená: stránky stejného druhu opakují volným textem stejné údaje, pro které vzor nemá místo (u reklamace dodavatel, dodací list, lhůta).
- Při prvním výskytu použij nejbližší vzor a do deníku zapiš `vzor prace použit pro <druh>`.
- Když se v deníku stejná poznámka objeví **podruhé**, navrhni nový typ: jak se jmenuje, kdy se použije, jaké má oddíly (nejvýš šest).
- Po souhlasu ulož vzor do `Claude-mozek/vzory/<typ>.md`, založ pro typ složku a obě dosavadní stránky do ní převeď.
- Když uživatel některý oddíl třikrát nechá prázdný, navrhni ho vyřadit.

## Atomizace

Jedna stránka, jedna věc.

- Stránku nad 150 řádků nebo se dvěma samostatnými tématy rozděl.
- Na původním místě nech shrnutí na pár řádků a odkazy na nové stránky, takže staré odkazy platí.
- Seznamové soubory (`lide.md`, `slovnik.md`, `rozhodnuti.md`) děl podle přirozené hranice: firma, oblast, rok.

## Archivace

Dokončenou práci po souhlasu:

1. přesuň do `archiv/RRRR/`,
2. v archivované stránce přepiš stav na `Hotovo, archivováno RRRR-MM-DD`,
3. odstraň ji z `PREHLED.md`,
4. v `REJSTRIK.md` nech jeden řádek s cestou do archivu,
5. oprav odkazy ve `vlakna.md` a na jiných stránkách.

Uzavřené otázky a vlákna starší než čtvrt roku přesuň do `archiv/RRRR/`. Nic nemaž. Archiv čti jen na vyžádání. Práce, na kterou se dva měsíce nesáhlo, není hotová: zeptej se, jestli je odložená, zrušená, nebo hotová.

## Plán větší práce

Když práce zabere víc než jedno sezení nebo má víc než pět kroků, navrhni jí složku `prace/<nazev>/` se souborem `plan.md` podle vzoru `assets/vzory/plan.md`. Když je to zřejmé už při zadání, navrhni plán hned, ne až příště.

- **Další krok žije jen v plánu.** Stránka práce, pokud existuje, nese cíl a odkaz na plán; `PREHLED.md` jednu větu o stavu. Nic z toho další krok neopisuje.
- Každé sezení na té práci začni přečtením plánu a řekni jednou větou, kde jste skončili.
- U kroků s datem, které už prošlo, se zeptej, jestli jsou hotové, a podle odpovědi je odškrtni nebo přeplánuj.
- Plán opravuj průběžně, hlavně „Další krok“. Kroky cizí práce do něj nepatří.

## Větev pro velkou složku

Složka s víc než třiceti dokumenty dostane po souhlasu větev `vetve/<nazev>/` podle vzoru `assets/vzory/vetev.md`: k čemu složka je, jak je uspořádaná, jeden řádek o každém dokumentu nebo skupině, kterou už znáš, a stránky pro to, co se používá opakovaně. Nabídni ji jednou konkrétní větou, jakmile takovou složku poznáš: „Mám si složku Smlouvy zapsat jako přehled po skupinách, ať ji příště nemusím číst celou?“

- Po založení smaž z `mapa-slozek.md` všechny řádky o té složce kromě jednoho s odkazem na větev.
- Větev stav postupně, jak dokumenty při práci opravdu čteš. Celou složku čti jen na žádost a podle `pruzkum.md`.
- Do větve patří výtahy a odkazy, nikdy kopie dokumentů.
- U každého výtahu uveď cestu a **datum změny souboru na disku** (ne datum čtení; když ho nezjistíš, napiš `neznámé`) a datum, kdy jsi soubor četl. Když je soubor novější než tvoje čtení, výtah je podezřelý: přečti soubor znovu a řekni, co se změnilo.
- Když podsložka přeroste třicet dokumentů nebo `INDEX.md` 150 řádků, založ pod větví další větev stejným způsobem.

### Větev přímo ve složce klienta nebo projektu

Výchozí je větev v mozku. Přímo ve složce (`<složka>/_mozek/INDEX.md` a stránky vedle něj) ji založ jen tehdy, když si o to uživatel řekne. Sám ji navrhni jen tehdy, když uživatel zmíní, že složku sdílí s kolegy, kteří s ní také pracují přes Clauda, nebo že má pro každého klienta zvláštní projekt.

- Před založením řekni jednou větou: „Tyhle poznámky uvidí každý, kdo má ke složce přístup.“
- Do místní větve patří jen věci o té složce a práci v ní: co kde je, výtahy, stav, plán, rozhodnutí o té věci.
- Nikdy do ní nepatří nic osobního: `jak-pracuju.md`, `ucitel.md`, `vlakna.md`, otázky a poznámky o lidech mimo ten projekt. Ty zůstávají jen v `Claude-mozek`. Citlivé údaje do ní nesmí stejně jako do mozku.
- V `mapa-slozek.md` a `REJSTRIK.md` na ni veď jeden řádek s cestou a poznámkou `místní větev`.
- Když složka s místní větví není v sezení připojená, řekni to a pracuj jen s tím, co je v mozku.
- Když je připojená složka s `_mozek/`, ale `Claude-mozek` ne, smíš místní větev číst a doplňovat; osobní paměť nezakládej a nabídni `/mozek:start`.

## Postup a vlastní skill

- Opakování počítej jen z řádků deníku se stejným štítkem `[úloha: název]`. Když uživatel sám řekne, pokolikáté to dělá, věř jemu. Nepiš do postupu vyšší počet, než jsi našel.
- Při třetím opakování nabídni sepsat postup do `postupy/` (pokud to hlasitost dovoluje). Postup napiš až po „ano“.
- Postup použitý pětkrát nabídni převést na vlastní skill uživatele nebo na plánovanou úlohu a jednou větou řekni, co tím získá.
