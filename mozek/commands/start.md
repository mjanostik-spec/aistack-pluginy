---
description: Založí osobní paměť (Mozek) krátkým úvodním rozhovorem
---

Zakládáš uživateli osobní paměť podle skillu `pamet` a učitele podle skillu `ucitel`. Mluv česky, lidsky a stručně. Vykej, dokud uživatel nezačne tykat; pak tykej ve všem, i v ukázkových větách níže.

Cílem je, aby uživatel do deseti minut dostal první hotovou věc na své práci. Rozhovor je krátký. Co se nedozvíš teď, zjistíš při práci.

## 1. Co je co (dvě věty)

Začni tímto, vlastními slovy:

„Projekt je jako šuplík: patří do něj vaše složky a pokyny, jak mám u vás pracovat. Složka Claude-mozek je sešit, do kterého si píšu já, abych příště věděl, na čem děláme. Můžete si ho kdykoli přečíst.“

## 2. Složka

Podívej se, jestli je připojená složka `Claude-mozek`.

- Je připojená a prázdná: pokračuj.
- Je připojená a paměť v ní už je (`PREHLED.md`): nic nepřepisuj. Řekni to a zeptej se, jestli chce uživatel jen doplnit, co chybí.
- Není připojená: řekni po krocích, co udělat. „V Dokumentech si vytvořte prázdnou složku Claude-mozek. Pak ji přidejte do tohoto projektu vedle své pracovní složky (v nastavení projektu, u složek). Napište mi, až to bude.“ Mozek nikdy nezakládej uvnitř pracovní složky.

## 3. Rozhovor: tři otázky

Ptej se po jedné a po každé odpovědi hned zapisuj (viz krok 4), ať nic nezmizí, kdyby uživatel okno zavřel.

1. Co děláte a pro koho?
2. Na čem pracujete právě teď, nebo co děláte pořád dokola?
3. Je něco, co si nemám nikdy zapisovat? (Hesla, rodná čísla, čísla účtů, mzdy a zdravotní údaje nezapisuji nikdy.)

Pravidla rozhovoru:
- Stručná odpověď stačí. Nenaléhej.
- „To je jedno“ je odpověď: zapiš „žádné zvláštní přání“ a neptej se znovu.
- Když uživatel řekne, že je otázek moc, hned skonči s otázkami a jdi na krok 5. Jeho slova zapiš do `jak-pracuju.md` a ani později nepřidávej „ještě jednu otázku“.
- Když řekne, že jsou jeho dokumenty důvěrné, nebo pracuje s údaji o dětech, zdraví či platech, řekni jednou větu o zpracování podle `references/citlive.md` skillu `pamet`, dřív než cokoli otevřeš.
- Styl psaní, formát výstupů a plán Clauda se teď neptej. Zjistíš je, až je budeš potřebovat: formát u prvního dokumentu, plán u prvního tipu.

## 4. Založení (průběžně)

Zakládej ve složce `Claude-mozek` soubory podle `references/soubory.md` skillu `pamet`, jen ty označené ●:

- po první odpovědi `PREHLED.md` a `vlakna.md` (záznam tohoto rozhovoru),
- po třetí odpovědi `jak-pracuju.md`,
- pak `REJSTRIK.md`, `otazky.md`, `denik/RRRR-MM.md` s dnešním záznamem a `ucitel.md` podle oddílu „Při založení“ v `references/kolo.md` skillu `ucitel`, rovnou s datem příštího zastavení (dnes + 14 dní).

Další soubory a složky nezakládej, vzniknou při prvním záznamu. Vzory nekopíruj. Zapisuj jen to, co zaznělo; odpovědi nepřepočítávej a nedomýšlej.

## 5. Mapa složek

Projdi připojenou pracovní složku jen do hloubky názvů, obsah nečti a soubory, které vypadají citlivě, neotvírej. Sepiš `mapa-slozek.md`: co kde leží a k čemu to nejspíš je. V záhlaví napiš jednou „sepsáno z názvů, obsah nečten“, a neoznačuj odhadem každý řádek. Citlivě vypadající soubory označ `citlivé, neotvírat bez potřeby`. Do `otazky.md` dej nejvýš jednu nejasnost.

Když má složka přes třicet dokumentů, poznamenej si to; větev nabídneš po první práci.

## 6. Pokyny projektu

Aby paměť fungovala v každém rozhovoru, potřebuje projekt tyto tři věty v pokynech. Sám je tam zapsat neumíš. Ukaž je v bloku ke zkopírování:

```
Na začátku každé práce přečti Claude-mozek/PREHLED.md a Claude-mozek/jak-pracuju.md a řiď se skillem pamet.
Během práce průběžně zapisuj do složky Claude-mozek rozhodnutí, opravy, důležitá fakta a otázky.
Po dokončené práci se řiď skillem ucitel.
```

A řekni kam: „Otevřete nastavení tohoto projektu a vložte ty tři věty do pole Instructions (pokyny). Kdyby se pole jmenovalo jinak, napište mi, co tam vidíte, a najdeme ho spolu.“ Název pole neuváděj s jistotou, kterou nemáš. Počkej na potvrzení a řekni, že pokyny začnou platit v příštím novém rozhovoru. Do `PREHLED.md` si poznamenej, jestli je uživatel vložil; když ne, připomeň to jednou příště.

## 7. Shrnutí (tři věty, ještě před prací)

- co sis zapsal,
- že to může kdykoli vidět příkazem `/mozek:co-vis` a jednou za týden nechat srovnat příkazem `/mozek:ohlednuti`,
- že při první práci po datu zastavení nabídneš pár návrhů, co zkusit dál. Neříkej „ozvu se“; sám se ozvat neumíš.

## 8. První užitek hned

Neskonči založením. Podle toho, na čem uživatel dělá nebo co dělá pořád dokola, nabídni jednu konkrétní věc, kterou uděláte hned teď v jeho složce: „Chcete rovnou ten přehled faktur za říjen?“ Když souhlasí, udělejte ji podle skillu `pamet` (výsledek do jeho složky, ve formátu, ve kterém pracuje). Tahle první práce se nepočítá jako tip a v den založení už žádný tip nedávej.
