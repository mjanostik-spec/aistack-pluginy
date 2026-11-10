# Soubory ve složce Claude-mozek

Každá stránka začíná nadpisem a jednou větou, o čem je. Data piš jako RRRR-MM-DD.

| Soubor | Co v něm je | Limit |
|---|---|---|
| `PREHLED.md` | Horká paměť: kdo uživatel je, na čem teď dělá, klíčoví lidé, co se blíží, kam dál. Čte se na začátku každé práce. | 80 řádků |
| `jak-pracuju.md` | Pravidla z oprav uživatele: jak co chce mít, co je u něj citlivé. Čte se na začátku každé práce. | 60 řádků |
| `REJSTRIK.md` | Jeden řádek na každou stránku mozku: cesta a jedna věta. | 150 řádků |
| `mapa-slozek.md` | Co kde na disku leží a k čemu to je. U velkých složek jen řádek s odkazem na větev. | 150 řádků |
| `prace\<nazev>.md` | Stránka jedné věci, na které uživatel dělá: cíl, stav, další krok, souvislosti. | 150 řádků |
| `prace\<nazev>\plan.md` | Plán větší práce. Viz `stavba.md`. | 150 řádků |
| `postupy\<nazev>.md` | Opakovaná úloha krok za krokem. | 150 řádků |
| `vetve\<nazev>\INDEX.md` | Vnořená wiki pro složku s mnoha dokumenty. Viz `stavba.md`. | 150 řádků |
| `vzory\` | Vzory typů stránek. Nové přibývají podle práce. | |
| `lide.md` | Kdo je kdo: jméno, role, firma, na čem s uživatelem dělá. | 150 řádků |
| `slovnik.md` | Zkratky, názvy a pojmy, které uživatel používá. | 150 řádků |
| `rozhodnuti.md` | Co se rozhodlo, kdy a proč. Nejnovější nahoře. | 150 řádků |
| `otazky.md` | Otevřené otázky nahoře s prioritou, uzavřené dole. | 150 řádků |
| `terminy.md` | Data a lhůty z dokumentů a rozhovorů. Prošlé se při ohlédnutí odsouvají. | 80 řádků |
| `schranka.md` | Rychlé „zapamatuj si“. Třídí se při ohlédnutí. | 40 řádků |
| `vlakna.md` | Index rozhovorů. Viz `vlakna.md` v této složce příloh. | 150 řádků, starší do archivu |
| `denik\RRRR-MM.md` | Co se kdy udělalo, jeden až tři řádky na den práce. Nový soubor každý měsíc. | |
| `ucitel.md` | Vede skill `ucitel`: co uživatel umí, cíle, plán. Skill paměti do něj nezapisuje. | |
| `archiv\RRRR\` | Dokončené práce, staré otázky a stará vlákna. Čte se jen na vyžádání. | |

## PREHLED.md

```
# Přehled
Horká paměť: to nejdůležitější o uživateli a jeho práci. Poslední úprava RRRR-MM-DD.

## Kdo jsem
## Na čem teď dělám
- [název práce](prace/nazev.md): stav jednou větou, další krok
## Klíčoví lidé
## Co se blíží
## Kde co je
```

Do přehledu patří jen to, co se používá teď. Co se měsíc nepoužilo, přesuň na stránku nebo do archivu a nech po něm řádek v rejstříku.

## Deník

```
## 2026-11-10
- Uzávěrka říjen: spárováno 42 faktur, chybí 3 (seznam v prace/uzaverka-rijen.md).
```

Deník říká, co se stalo, ne jak. Podle deníku poznáš, že se něco dělá potřetí.
