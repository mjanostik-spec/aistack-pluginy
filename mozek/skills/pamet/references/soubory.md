# Soubory ve složce Claude-mozek

Každá stránka začíná nadpisem a jednou větou, o čem je. Data piš jako RRRR-MM-DD. Cesty piš s obyčejným lomítkem.

Při založení vznikají jen soubory označené ●. Ostatní založ až při prvním záznamu.

| Soubor | Co v něm je | Limit |
|---|---|---|
| ● `PREHLED.md` | Horká paměť: kdo uživatel je, na čem teď dělá, klíčoví lidé, co se blíží. Čte se na začátku každé práce. | 80 řádků |
| ● `jak-pracuju.md` | Obecná přání uživatele: jak chce pracovat, co je citlivé, jaký formát výstupů. Čte se na začátku každé práce. | 60 řádků |
| ● `REJSTRIK.md` | Jeden řádek na každou stránku mozku: cesta a k čemu stránka je. Bez čísel, dat a stavů, ty zastarávají. | 150 řádků |
| ● `mapa-slozek.md` | Co kde na disku leží a k čemu to je. U složky s větví jen jeden řádek s odkazem. | 150 řádků |
| ● `otazky.md` | Otevřené otázky nahoře s prioritou, uzavřené dole. | 150 řádků |
| ● `vlakna.md` | Index rozhovorů. Viz `vlakna.md` v přílohách. | 150 řádků |
| ● `ucitel.md` | Zakládá ho `/mozek:start`, dál ho vede jen skill `ucitel`. | |
| ● `denik/RRRR-MM.md` | Co se kdy udělalo, jeden až tři řádky na den práce. Nový soubor každý měsíc. | |
| `terminy.md` | Řádky začínající datem v budoucnosti, opakované úkoly a úkoly uživatele. Čte se na začátku každé práce. | 80 řádků |
| `rozhodnuti.md` | Co se rozhodlo a kdy; proč, když zaznělo. Nejnovější nahoře. | 150 řádků |
| `lide.md` | Kdo je kdo: jméno, role, firma, jak s ním uživatel jedná. | 150 řádků |
| `slovnik.md` | Zkratky, názvy a pojmy, které uživatel používá. | 150 řádků |
| `schranka.md` | „Zapamatuj si“, u kterého není jasné, kam patří. Třídí se při ohlédnutí. | 40 řádků |
| `prace/<nazev>.md` | Stránka jedné věci, na které uživatel dělá. | 150 řádků |
| `prace/<nazev>/plan.md` | Plán větší práce. Viz `stavba.md`. | 150 řádků |
| `postupy/<nazev>.md` | Opakovaná úloha krok za krokem. | 150 řádků |
| `vetve/<nazev>/INDEX.md` | Přehled složky s mnoha dokumenty. Viz `stavba.md`. | 150 řádků |
| `vzory/` | Jen vzory, které jste s uživatelem upravili nebo nově vytvořili. | |
| `archiv/RRRR/` | Dokončené práce, staré otázky a vlákna. Čte se jen na vyžádání. | |

## PREHLED.md

```
# Přehled
Horká paměť: to nejdůležitější o uživateli a jeho práci.
Založeno RRRR-MM-DD · poslední úprava RRRR-MM-DD · poslední úklid RRRR-MM-DD (nebo: zatím žádný)
Učitel: příští zastavení RRRR-MM-DD · tipy: běžně | míň | žádné · zastavení: ano | na požádání

## Kdo jsem
(role, firma, s kým pracuje. Jméno jen když ho řekl. Žádné hodnocení schopností ani povahy.)

## Na čem teď dělám
- [název práce](prace/nazev.md): stav jednou větou. Další krok je v plánu práce, a když plán není, na stránce práce.

## Klíčoví lidé
- Jméno, role jednou větou. (nejvýš pět; podrobnosti v lide.md)

## Co se blíží
- (nejvýš pět nejbližších řádků z terminy.md)

## Čeká na souhlas
- RRRR-MM-DD: navrhl jsem … (smaž po odpovědi)
```

Do přehledu patří jen to, co se používá teď. Hotovou práci z něj odstraň hned, jak se o tom dozvíš. Co se měsíc nepoužilo, přesuň na stránku nebo do archivu. Provozní poznámky (jestli jsou vložené pokyny projektu) do přehledu nepatří; ty dej do `jak-pracuju.md` na konec.

## terminy.md

```
# Termíny
Co se blíží a co má uživatel udělat.

## Blíží se
- 2026-12-10: platnost nabídky Strojírny Hodonín. (soubor pracovni/nabidky/hodonin.md)
- každé pondělí: přehled lhůt pro pana ředitele. (řekl uživatel; 2026-11-25)
- bez data: říct paní Mrázkové o změně rozvrhu. (řekl uživatel; 2026-11-13)

## Prošlé
- ~~2026-11-14: uzávěrka října~~ (splněno 2026-11-13)
- 2026-11-20: montáž kuchyně Hájek. (výsledek neznámý, otázka v otazky.md)
```

Datum na začátku řádku je vždy datum události, ne zápisu. Řádky řaď podle data. Co zaznělo nejistě, zapiš jako `nepotvrzeno: <co a kdy asi>` na konec oddílu. Do termínů nepatří události, které se už staly (ty jsou v deníku), stav práce ani zastavení s učitelem (to vede `ucitel.md`). Prošlý termín přesuň do „Prošlé“ až po zjištění, jak dopadl; do té doby je `výsledek neznámý`.

## Deník

```
## 2026-11-10
- Uzávěrka říjen: spárováno 42 faktur, chybí 3 (seznam na stránce práce). [úloha: párování faktur]
```

Deník říká, co se stalo, ne jak. Práci označ štítkem `[úloha: název]` podle druhu práce (`cenová nabídka`, ne `nabídka Kobliha`), vždy stejným; podle něj se počítá, kolikrát se dělala.
