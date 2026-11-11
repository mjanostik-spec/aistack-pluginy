# Stavba paměti: jak roste a nezarůstá

Prahy jsou orientační. Když je důvod udělat změnu dřív nebo později, udělej ji.

**Vnitřní stavbu dělej sám.** Plán práce, přehled velké složky, rozdělení stránky, nový typ stránky a archivace jsou tvoje pracovní poznámky. Neptej se na ně a nevysvětluj je. Uživateli řekni nejvýš jednou větou, co mu to přinese, a jen když se to hodí. Po každé změně oprav `REJSTRIK.md` a odkazy, které na změněné stránky vedou, a zapiš řádek do deníku.

**Na souhlas čekej jen u toho, co se týká uživatele:** postup nebo skill, který bude používat, plánovaná úloha, poznámky přímo v jeho složce (místní přehled). Souhlas je výslovné „ano“. Odpověď typu „jak myslíte“ souhlas není. Nabídka bez odpovědi patří do `PREHLED.md` pod „Čeká na souhlas“ a vrátíš se k ní při ohlédnutí. Tyto nabídky se řídí hlasitostí tipů (skill `ucitel`): když má uživatel tipy vypnuté nebo si návrhy omezil, při práci je nenabízej.

Uživateli neříkej slova „větev“, „rejstřík“, „atomizace“. Říkej „přehled složky“, „seznam stránek“, „rozdělil jsem si poznámky“.

## Nové typy stránek

Vzory jsou v `assets/vzory/` tohoto skillu: práce, postup, člověk nebo firma, plán, větev. Práce každého člověka je jiná, takže typy přibývají.

- Každou stránku práce označ v deníku štítkem `[úloha: název]`, vždy stejným pro stejný druh práce.
- Když se stejný štítek objeví podruhé, porovnej obě stránky. Opakují-li volným textem stejné údaje, pro které vzor nemá místo (u reklamace dodavatel, dodací list, lhůta; u nabídky zákazník, platnost, sleva), založ nový typ: vzor do `Claude-mozek/vzory/<typ>.md` s nejvýš šesti oddíly, složku pro typ, a obě stránky do ní převeď.
- Oddíl, který zůstal třikrát prázdný, ze vzoru vyřaď.

## Atomizace

Jedna stránka, jedna věc. Stránku nad 150 řádků nebo se dvěma samostatnými tématy rozděl; na původním místě nech shrnutí a odkazy, takže staré odkazy platí. Seznamové soubory děl podle přirozené hranice: firma, oblast, rok.

## Archivace

Jakmile se dozvíš, že je práce hotová, odstraň ji z `PREHLED.md` a přepiš stav její stránky. Při ohlédnutí, nebo když stránek přibývá, ji archivuj:

1. přesuň do `archiv/RRRR/`,
2. stav přepiš na `Hotovo, archivováno RRRR-MM-DD`,
3. v `REJSTRIK.md` nech jeden řádek s cestou do archivu,
4. oprav odkazy ve `vlakna.md` a na jiných stránkách.

Uzavřené otázky a vlákna starší než čtvrt roku přesuň do `archiv/RRRR/`. Nic nemaž. Archiv čti jen na vyžádání. Práce, na kterou se dva měsíce nesáhlo, není hotová: při ohlédnutí se zeptej, jestli je odložená, zrušená, nebo hotová.

## Plán větší práce

Když práce zabere víc než jedno sezení nebo má víc než pět kroků, založ jí složku `prace/<nazev>/` se souborem `plan.md` podle vzoru `assets/vzory/plan.md`. U jednorázové věci na jedno sezení plán nezakládej.

- **Další krok žije jen v plánu.** Stránka práce, pokud existuje, nese cíl a odkaz na plán; `PREHLED.md` jednu větu o stavu.
- Každé sezení na té práci začni přečtením plánu a řekni jednou větou, kde jste skončili.
- U kroků s datem, které už prošlo, se zeptej, jestli jsou hotové (počítá se jako termín v „jedné věci navíc“).
- Plán opravuj průběžně, hlavně „Další krok“. Kroky cizí práce do něj nepatří.
- Když uživatel chce plán vidět nebo poslat dál, udělej mu z něj dokument v jeho složce.

## Přehled velké složky (větev)

Složce s víc než třiceti dokumenty založ `vetve/<nazev>/INDEX.md` podle vzoru `assets/vzory/vetev.md`: k čemu složka je, jak je uspořádaná, řádek o každém dokumentu nebo skupině, kterou už znáš.

- Stav ho z toho, co při práci opravdu čteš. Kvůli přehledu nečti nic navíc; celou složku procházej jen na žádost a podle `pruzkum.md`.
- Po založení nech v `mapa-slozek.md` o složce jediný řádek s odkazem.
- Do přehledu patří výtahy a odkazy, nikdy kopie dokumentů. U smluv a podobných dokumentů zapiš i jejich lhůty do `terminy.md`.
- U každého výtahu uveď cestu, **datum změny souboru na disku** (když ho nezjistíš, `neznámé`) a datum čtení. Když je soubor novější než tvoje čtení, přečti ho znovu a řekni, co se změnilo. Když uživatel řekne, že data změny nejsou spolehlivá (synchronizace), zapiš to do přehledu a důležité soubory před použitím ověřuj obsahem.
- Když podsložka přeroste třicet dokumentů nebo `INDEX.md` 150 řádků, založ pod ním další přehled stejným způsobem.

### Poznámky přímo ve složce klienta nebo projektu

Výchozí je přehled v mozku. Přímo ve složce (`<složka>/_mozek/INDEX.md` a stránky vedle něj) ho založ jen se souhlasem. Nabídni to, když uživatel řekne, že složku sdílí s kolegy, kteří s ní také pracují přes Clauda, že má pro každého klienta zvláštní projekt, nebo že chce mít poznámky u dokumentů.

- Před založením řekni jednou větou: „Tyhle poznámky uvidí každý, kdo má ke složce přístup.“
- Patří do nich jen věci o té složce a práci v ní: co kde je, výtahy, stav, plán, rozhodnutí o té věci.
- Nikdy do nich nepatří nic osobního: `jak-pracuju.md`, `ucitel.md`, `vlakna.md`, otázky a poznámky o lidech mimo ten projekt. Ty zůstávají jen v `Claude-mozek`. Citlivé údaje do nich nesmí stejně jako do mozku.
- V `mapa-slozek.md` a `REJSTRIK.md` na ně veď jeden řádek s cestou a poznámkou `místní přehled`.
- Když složka není v sezení připojená, řekni to a pracuj jen s tím, co je v mozku.
- Když je připojená složka s `_mozek/`, ale `Claude-mozek` ne, smíš místní poznámky číst a doplňovat; osobní paměť nezakládej a nabídni `/mozek:start`.

## Postup a vlastní skill

- Opakování počítej jen z řádků deníku se stejným štítkem `[úloha: název]`. Když uživatel sám řekne, pokolikáté to dělá, věř jemu.
- Při třetím opakování si poznamenej do `PREHLED.md` pod „Čeká na souhlas“, že úloha zaslouží postup, a nabídni ho jako tip (podle pravidel učitele) nebo při ohlédnutí: „Tohle děláme potřetí. Mám si sepsat postup, ať je to příště rychlejší a stejné?“ Postup napiš až po „ano“.
- Postup použitý pětkrát nabídni převést na vlastní skill uživatele nebo na plánovanou úlohu a jednou větou řekni, co tím získá.
