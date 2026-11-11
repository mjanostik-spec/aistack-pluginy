# Zápis do paměti: tvar, zdroje, co kam patří

## Tvar záznamu

```
- Dobropisy účtujeme do měsíce vystavení. (řekl uživatel; 2026-11-10; vlákno: Uzávěrka říjen, 4. zpráva, „dobropisy patří do měsíce vystavení“)
- Ing. Černá, ředitelka, schvaluje uzávěrku. (soubor pracovni/poznamky-uzaverka.txt; 2026-11-10)
- Poslední den pro výpověď je 2026-12-31. (výpočet z pracovni/smlouva-12.txt: konec 2027-03-31 minus tři měsíce; 2026-11-10)
- Nabídky pro firmy počítáme s DPH 21 %. (návrh Claude, uživatel přijal pro nabídku Pekárna; 2026-11-25; otázka, zda platí obecně)
- „ŘP“ je nejspíš ředitel provozu. (odhad ze zápisu z porady; 2026-11-10; otázka v otazky.md)
```

Každý záznam má **datum** a **jeden zdroj**:

| Zdroj | Kdy |
|---|---|
| `řekl uživatel` | Jen to, co uživatel řekl. Když si nebyl jistý („asi“, „myslím“), připiš `nejistě` a nech otázku otevřenou. |
| `návrh Claude, uživatel přijal` | Navrhl nebo spočítal jsi to ty a uživatel řekl ano. Platí pro ten jeden případ. |
| `soubor <cesta>` | Údaj stojí v souboru, který uživatel má. |
| `výstup <cesta>` | Údaj stojí v dokumentu, který jsi vytvořil ty. |
| `výpočet z <čeho>` | Údaj v souboru není, spočítal jsi ho. Uveď jak. |
| `odhad` | Odvodil jsi to, zobecnil, nebo to víš obecně (význam zkratky). |

Pravidla:

- **Jeden záznam, jeden zdroj.** Co uživatel řekl a co sis k tomu domyslel, jsou dva řádky. „Podle ceníku“ je `řekl uživatel`; „tedy bez slevy“ je `odhad`.
- **Odhad a nevyřešená nesrovnalost mají vždy otázku** v `otazky.md` (částka nesedí, údaj chybí, něco sis domyslel). Bez otázky by se na ně nikdo nezeptal. Výjimka: odhad v hotovém dokumentu, který tam viditelně označíš a uživatel ho uvidí.
- **Obecné a jednotlivé.** Obecná formulace („vždy“, „nikdy“, „u nás se to dělá“, „pořád“, „dobropisy patří do…“) stačí jako pravidlo, neptej se znovu. Pokyn vázaný na jeden dokument („tenhle dopis kratší“) zapiš na stránku té práce. Podruhé stejný pokyn u jiné práce z něj dělá pravidlo.
- **Pravidlo jen pro jednu zakázku, klienta nebo projekt** patří na stránku té práce do „Dohodnuto pro tuto práci“, ne do `jak-pracuju.md`.
- **Do `jak-pracuju.md` jen to, co uživatel řekl nebo výslovně přijal.** Tvoje domněnky (formát, kdo co odesílá) patří na stránku práce a do `otazky.md`.
- **Pokyn k práci, který stojí v uživatelově souboru** („částky bez haléřů“), zapiš na stránku práce se zdrojem `soubor`; až se úloha zopakuje, přenes ho do postupu.
- **Uvozovky jen doslovně.** Vlastní shrnutí piš bez uvozovek.
- **Důvod jen když zazněl.** Jinak napiš `důvod nezazněl`.
- **Dobu a množství nepřepočítávej.** „Mám to týden“ zapiš jako „k 2026-11-10 asi týden“.
- **Odkaz „viz X“** napiš, jen když údaj v X opravdu je.
- **Jméno uživatele** zapiš a používej, jen když ho řekl. Jméno z názvu souboru je odhad.

## Odkaz na rozhovor

Odkaz na vlákno (`vlákno: <název>, <kde>, „<kotva>“`) uveď u rozhodnutí a u pravidel v `jak-pracuju.md`, tedy tam, kde může být později spor o to, co zaznělo. U běžných faktů stačí datum a zdroj. Jak zapsat místo a kotvu, je ve `vlakna.md`.

## Oprava a spor

- **Údaj zastaral:** `~~starý údaj~~ (neplatí od RRRR-MM-DD, nahrazeno: …)`.
- **Uživatel řekl nově něco jiného než dřív:** novější výslovný pokyn platí; starý přeškrtni.
- **Změnil se zdrojový soubor:** starý údaj přeškrtni, nový zapiš s datem změny souboru a řekni to uživateli.
- **Dva zdroje stejné váhy si odporují** (dva dokumenty, dokument proti tomu, co řekl uživatel): nech oba, zapiš `SPOR: <co> proti <čemu> (viz otazky.md)` a otázku priority A. Uživateli řekni, který zdroj je podle tebe novější nebo závaznější a proč, ale rozhodnutí nech na něm. Když z dokumentu zapisuješ termín, projdi v něm všechna data a porovnej je s `terminy.md`.
- **Časově omezený údaj** (dovolená, zastupování) po skončení přeškrtni: `~~údaj~~ (skončilo RRRR-MM-DD)`.

## Co kam patří

| Co zaznělo nebo jsi zjistil | Kam |
|---|---|
| Obecné přání, jak pracovat, co nikdy nepsat, jaký formát | `jak-pracuju.md` |
| Trvalé pravidlo, které je zároveň rozhodnutí („reklamace nad 20 tisíc vždy i řediteli“) | `jak-pracuju.md`; v `rozhodnuti.md` jen datum, jedna věta a „viz jak-pracuju.md“ |
| Rozhodnutí v jedné věci, pravidlo jedné zakázky | stránka práce a `rozhodnuti.md` |
| Jak jednat s konkrétním člověkem (tykání, oslovení, podpis) | `lide.md` u toho člověka |
| Člověk, firma, role, vztah k uživateli (i z dokumentu) | `lide.md`; jen ti, se kterými se pracuje |
| Zkratka, název, pojem | `slovnik.md` |
| Cokoli s datem nebo opakováním, i když to zaznělo jako „zapamatuj si“ | `terminy.md` a stránka práce |
| Úkol uživatele („říct paní Mrázkové…“) | `terminy.md` (s datem, nebo `bez data`) |
| „Zapamatuj si…“ a je jasné, kam to patří | rovnou tam |
| „Zapamatuj si…“ a nevíš, kam to patří | `schranka.md` |
| Stav práce, další krok | `plan.md`, nebo stránka práce, když plán není; v `PREHLED.md` jen jedna věta |
| Nesrovnalost: čísla dokladů, které chybí nebo nesedí, a o kolik („FP-2026-1005: platba o 90 Kč nižší“) | stránka práce, jednou větou; celé tabulky ne, na ty odkaž |
| Nevyřešená položka | `otazky.md`; stránka práce a plán na ni jen odkážou |
| Uživatel odmítl nabídku nebo si něco hlídá sám | `jak-pracuju.md`, jednou větou s datem |
| Co se stalo dnes | `denik/RRRR-MM.md` se štítkem `[úloha: název]` |
| Co kde leží | `mapa-slozek.md` nebo přehled složky |
| Poznatek o tom, jak uživatel používá Clauda | nic; to vede skill `ucitel` |

Jeden údaj má jeden domov. Jinde na něj odkaž, neopisuj ho. Jediná povolená kopie je `PREHLED.md`: nese krátké věty bez zdrojů a při změně opravíš obojí hned, protože přehled čte příští Claude jako první.

Soubor, který ještě neexistuje, založ až při prvním záznamu.
