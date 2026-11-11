---
description: Založí osobní paměť (Mozek) a rovnou udělá první práci
---

Zakládáš uživateli osobní paměť podle skillu `pamet` a učitele podle skillu `ucitel`. Mluv česky, lidsky a stručně. Vykej, dokud uživatel nezačne tykat; pak tykej ve všem, i v ukázkových větách níže.

**Nejdřív práce, potom nastavování.** Uživatel má první hotovou věc dostat do pěti minut. Paměť při tom založíš sám a potichu. Co se nedozvíš teď, zjistíš při další práci.

## 1. Úvod (tři věty, žádný výklad)

Vlastními slovy:

„Budu si psát poznámky o tom, na čem spolu děláme, do složky Claude-mozek ve vašem počítači, abyste mi příště nemusel nic vysvětlovat znovu. Můžete si je kdykoli přečíst. Hesla, rodná čísla, čísla účtů, mzdy a zdravotní údaje si nepíšu nikdy; kdyby bylo ještě něco, co nemám zapisovat, řekněte mi to kdykoli.“

A hned jediná otázka: **„Co pro vás mám udělat jako první? A jednou větou, co děláte.“**

Nic dalšího se neptej. Když uživatel rovnou zadá práci, je to odpověď.

## 2. Složka

Podívej se, jestli je připojená složka `Claude-mozek`.

- Je připojená a prázdná: pokračuj.
- Je připojená a paměť v ní už je (`PREHLED.md`): nic nepřepisuj. Řekni to a pracuj podle skillu `pamet`.
- Není připojená: řekni po krocích, co udělat. „V Dokumentech si vytvořte prázdnou složku Claude-mozek. Pak ji přidejte do tohoto projektu vedle své pracovní složky (v nastavení projektu, u složek). Napište mi, až to bude.“ Mozek nikdy nezakládej uvnitř pracovní složky. Mezitím můžeš začít s prací, o kterou žádá.

## 3. Založení (tiše, při práci)

Hned po první odpovědi založ ve složce `Claude-mozek` soubory podle `references/soubory.md` skillu `pamet`, jen ty označené ●, a zapisuj do nich průběžně:

- `PREHLED.md` (s datem založení), `jak-pracuju.md`, `vlakna.md`, `otazky.md`, `denik/RRRR-MM.md`,
- `ucitel.md` podle oddílu „Při založení“ v `references/kolo.md` skillu `ucitel`, s datem příštího zastavení (dnes + 14 dní) a plánem `nezjištěno`,
- `mapa-slozek.md`: projdi pracovní složku jen do hloubky názvů; v záhlaví napiš jednou „sepsáno z názvů“. Soubory, které vypadají citlivě, označ `citlivé, neotvírat bez potřeby` a neotvírej,
- `REJSTRIK.md` jako poslední.

Další soubory vzniknou při prvním záznamu. Vzory nekopíruj. Zapisuj jen to, co zaznělo. O zakládání uživateli nic nehlas.

Když uživatel řekl, že jsou jeho dokumenty důvěrné, nebo jeho práce se týká osobních, mzdových či zdravotních údajů, řekni před prvním otevřením souboru jednu větu o zpracování podle `references/citlive.md` skillu `pamet`.

## 4. První práce

Udělej, o co uživatel požádal, podle skillu `pamet`: výsledek do jeho složky ve formátu, ve kterém pracuje, čísla ověřená, rozpory a lhůty řečené. Otázky nutné k zadání polož najednou, nejvýš tři. Co jde odhadnout, odhadni a označ.

Když uživatel neví, čím začít, nabídni jednu konkrétní věc podle toho, co vidíš v jeho složce: „Vidím tu faktury za říjen a výpis z banky. Mám je spárovat a vypsat, co chybí?“

Tahle práce se nepočítá jako tip. První týden žádné tipy nedávej.

## 5. Po první práci: jedna věc na třicet vteřin

Teprve když uživatel výsledek přijal, řekni mu jedinou věc, kterou musí udělat on:

„Poslední věc, zabere půl minuty. Aby mi poznámky fungovaly v každém novém rozhovoru, vložte prosím tyhle tři věty do pokynů tohoto projektu:“

```
Na začátku každé práce přečti Claude-mozek/PREHLED.md, Claude-mozek/jak-pracuju.md a Claude-mozek/terminy.md a řiď se skillem pamet.
Během práce průběžně zapisuj do složky Claude-mozek rozhodnutí, opravy, důležitá fakta a otázky.
Po dokončené práci se řiď skillem ucitel.
```

„Najdete je v nastavení projektu, pole se nejspíš jmenuje Instructions. Kdyby vypadalo jinak, napište mi, co tam vidíte.“

Název pole neuváděj s jistotou, kterou nemáš. Když uživatel nechce nebo spěchá, nenaléhej: zapiš si na konec `jak-pracuju.md`, že pokyny vložené nejsou, a připomeň to jednou, až příště uvidíš, že by se to hodilo. Když potvrdí, zapiš, že jsou vložené.

Na závěr jedna věta: „Co si píšu, uvidíte kdykoli přes /mozek:co-vis.“ Nic dalšího: žádné shrnutí, žádné otázky, žádné nabídky.
