# Průzkum složky

Uživatel chce, abys složku prošel, zmapoval a udělal si o ní poznámky. Výsledkem je větev v paměti (viz `stavba.md`). Průzkum má pevné hranice, aby ses nikdy nepustil do celého disku.

## Hranice (platí vždy, i když uživatel řekne „projdi všechno“)

1. **Jen na výslovnou žádost.** Průzkum nikdy nezačínej sám od sebe.
2. **Jen jedna jmenovaná složka,** která je připojená k projektu. Když uživatel složku nejmenuje, zeptej se která. Složku, která připojená není, neprocházej a řekni, že ji musí nejdřív připojit.
3. **Zakázané cíle.** Odmítni a požádej o užší složku, když je cílem:
   - kořen disku (`C:\`, `D:\`, `/`),
   - domovská složka uživatele nebo celé `Dokumenty`, `Plocha`, `Stažené soubory`, `Obrázky`,
   - kořen synchronizovaného úložiště (OneDrive, Google Disk, Dropbox, SharePoint),
   - systémové složky a složky programů,
   - složka `Claude-mozek` sama.
4. **Nevycházej ven.** Zástupce, odkazy a cesty vedoucí mimo jmenovanou složku nesleduj.
5. **Strop rozsahu.** Hloubka nejvýš tři úrovně pod jmenovanou složkou. Když má víc než 300 souborů nebo 50 podsložek, zastav se po prvním kroku a nech uživatele vybrat část.
6. **Strop čtení.** Obsah čti až po souhlasu a nejvýš 20 souborů na jedno kolo. Další kolo jen na další žádost.
7. **Co nečteš vůbec:** soubory, které vypadají citlivě (viz `citlive.md`), programy, archivy, zálohy, obrázky a videa, soubory nad 5 MB. Zapiš je jen názvem a poznámkou `nečteno`.
8. **Nic neměň.** Při průzkumu soubory jen čteš. Nepřesouváš, nepřejmenováváš, nemažeš.

Když si nejsi jistý, jestli je cíl dost úzký, zeptej se.

## Postup

**Krok 1: jen názvy.** Projdi názvy složek a souborů do hloubky tří úrovní. Nic neotvírej. Ohlas rozsah:

„Složka Zakázky má 6 podsložek a 84 souborů: 40 smluv, 22 tabulek, 18 e-mailů, 4 ostatní. Dva soubory vypadají citlivě a číst je nebudu.“

**Krok 2: návrh.** Navrhni, co přečteš, a počkej na souhlas:

„Přečtu 15 souborů, od každé skupiny pár nejnovějších, abych pochopil, jak to u vás chodí. Zbytek si zapíšu jen názvem. Souhlasíte, nebo chcete začít jinde?“

Vybírej to, co nejvíc vypoví: nejnovější soubory, přehledy a rejstříky, od každého druhu jeden až dva.

**Krok 3: čtení a zápis.** Po souhlasu čti a průběžně zapisuj do větve `vetve/<nazev>/` (nebo do místní větve, pokud ji uživatel chce):

- `INDEX.md`: k čemu složka je, jak je uspořádaná, tabulka dokumentů (soubor, co v něm je jednou větou, datum změny souboru, čteno kdy, nebo `nečteno`),
- lidé, pojmy a termíny, které se opakují, na jejich místa v paměti se zdrojem `soubor <cesta>`,
- otázky, které průzkum otevřel, do `otazky.md`.

Neopisuj obsah dokumentů. Výtah je jedna až tři věty.

**Krok 4: stav průzkumu.** Na konec `INDEX.md` zapiš:

```
## Stav průzkumu
- 2026-11-12: názvy celé složky (84 souborů), přečteno 15. Zbývá nečteno: smlouvy 2019 až 2023 (31), tabulky (18).
```

**Krok 5: zpráva.** Řekni v pěti řádcích, co jsi zjistil, co je nejasné (nejvýš dvě otázky) a co zbývá. Nabídni pokračování, nezačínej ho sám.

## Pokračování

Při dalším průzkumu téže složky začni oddílem „Stav průzkumu“ a čti jen to, co zbývá nebo co se od minula změnilo (podle data změny souboru). Nic nečti podruhé bez důvodu.
