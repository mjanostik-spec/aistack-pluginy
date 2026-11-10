---
description: Založí osobní paměť (Mozek) úvodním rozhovorem na pět až deset minut
---

Zakládáš uživateli osobní paměť podle skillu `pamet` a učitele podle skillu `ucitel`. Mluv česky, vykej, buď stručný. Ptej se po jedné otázce, ne dotazníkem.

## 1. Složka

Podívej se, jestli je připojená složka `Claude-mozek`.

- Když ano a je prázdná, pokračuj.
- Když ano a už v ní paměť je (`PREHLED.md`), nic nepřepisuj. Řekni to, ukaž, co v ní je, a zeptej se, jestli chce uživatel jen doplnit chybějící soubory.
- Když ne, vysvětli dvěma větami, co udělat: v Dokumentech vytvořit složku `Claude-mozek` a přidat ji do tohoto projektu vedle pracovní složky. Počkej, až to udělá. Když máš právo vytvářet složky v připojené pracovní složce, nezakládej mozek tam: paměť má ležet bokem.

## 2. Rozhovor

Řekni jednou větou, co vznikne: složka, do které si budeš psát, na čem spolu děláte, aby nemusel nic vysvětlovat dvakrát. Pak se zeptej postupně:

1. Co děláte a pro koho? (role, firma, s kým nejčastěji)
2. Co vám zabírá nejvíc času nebo co děláte pořád dokola?
3. Na čem pracujete právě teď?
4. Co je u vás citlivé a nemám si to nikdy zapisovat? (Hesla, rodná čísla, mzdy a zdravotní údaje nezapisuji nikdy.)
5. Jak mám psát a pracovat? (délka, tón, tykání nebo vykání, co vám u AI vadí)
6. Jaký máte plán Clauda a jak dlouho ho používáte?

Když uživatel odpoví stručně nebo otázku přeskočí, nenaléhej. Co nevíš, zapiš jako otázku.

## 3. Založení

Založ ve složce `Claude-mozek` soubory podle `references/soubory.md` skillu `pamet`:

- `PREHLED.md`, `jak-pracuju.md`, `REJSTRIK.md`, `mapa-slozek.md`, `lide.md`, `slovnik.md`, `rozhodnuti.md`, `otazky.md`, `terminy.md`, `schranka.md`, `vlakna.md`, `ucitel.md`,
- `denik\RRRR-MM.md` s dnešním záznamem,
- složky `prace\`, `postupy\`, `vetve\`, `archiv\`,
- `vzory\` s kopiemi vzorů z `assets/vzory/` skillu `pamet`.

Vyplň je tím, co zaznělo. Nevymýšlej nic navíc. Do `vlakna.md` zapiš tento rozhovor.

## 4. Mapa složek

Projdi připojenou pracovní složku jen do hloubky názvů složek a souborů, obsah zatím nečti. Sepiš `mapa-slozek.md`: co kde leží a k čemu to nejspíš je. Co jen odhaduješ, označ jako odhad a dvě až tři nejdůležitější nejasnosti dej do `otazky.md`. Složky nad třicet dokumentů si poznamenej jako kandidáty na větev, větev zatím nezakládej.

## 5. Pokyny projektu

Aby paměť fungovala v každém rozhovoru, potřebuje projekt tři věty v pokynech. Zkus je zapsat sám, pokud máš jak pokyny projektu nebo složky upravit. Když ne, ukaž je v bloku ke zkopírování a řekni, kam je vložit (pokyny projektu):

```
Na začátku každé práce přečti Claude-mozek\PREHLED.md a Claude-mozek\jak-pracuju.md a řiď se skillem pamet.
Během práce průběžně zapisuj do složky Claude-mozek rozhodnutí, opravy, důležitá fakta a otázky.
Po dokončené práci se řiď skillem ucitel.
```

## 6. První užitek hned

Neskonči založením. Podle toho, co uživatel řekl, že mu zabírá čas nebo na čem teď dělá, navrhni jednu konkrétní věc, kterou můžete udělat hned teď v jeho složce, a nabídni ji. Když souhlasí, udělejte ji.

## 7. Shrnutí

Na závěr třemi větami: co sis zapsal, že to může kdykoli vidět příkazem `/mozek:co-vis`, a že se za dva týdny ozveš s pár návrhy, co zkusit dál. Do `ucitel.md` nastav příští zastavení na dnešek + 14 dní.
