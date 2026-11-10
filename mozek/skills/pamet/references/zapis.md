# Zápis do paměti: tvar, zdroje, co kam patří

## Tvar záznamu

```
- Dobropisy účtujeme do měsíce vystavení. (řekl uživatel; 2026-11-10; vlákno: Uzávěrka říjen, ke konci, „dobropisy patří do měsíce vystavení“)
- Ing. Černá, ředitelka, schvaluje uzávěrku. (soubor pracovni/poznamky-uzaverka.txt; 2026-11-10)
- Poslední den pro výpověď je 2026-12-31. (výpočet z pracovni/smlouva-12.txt: konec 2027-03-31 minus tři měsíce; 2026-11-10)
- „ŘP“ je nejspíš ředitel provozu. (odhad ze zápisu z porady; 2026-11-10; otázka v otazky.md)
```

Každý záznam má **datum** a **jeden zdroj**:

| Zdroj | Kdy |
|---|---|
| `řekl uživatel` | Jen to, co uživatel řekl nebo výslovně potvrdil. Když si sám nebyl jistý, připiš `nejistě` a zapiš otázku. |
| `soubor <cesta>` | Údaj stojí v souboru. |
| `výpočet z <čeho>` | Údaj v souboru není, spočítal jsi ho. Uveď jak. |
| `odhad` | Odvodil jsi to, zobecnil, nebo to víš obecně (význam zkratky). Vždy zároveň otázka v `otazky.md`. |

Pravidla:

- **Jeden záznam, jeden zdroj.** Co uživatel řekl a co sis k tomu domyslel, jsou dva řádky. „Podle ceníku“ je `řekl uživatel`; „tedy bez slevy“ je `odhad`.
- **Pravidlo z jednoho případu není pravidlo.** Když uživatel řekl něco k jednomu dokumentu, zapiš to na stránku té práce. Do `jak-pracuju.md` to patří, až když to řekl obecně, nebo se zeptej: „Platí to i pro příště?“
- **Uvozovky jen doslovně.** Vlastní shrnutí piš bez uvozovek.
- **Důvod jen když zazněl.** Jinak napiš `důvod nezazněl`. Nedomýšlej ho.
- **Dobu a množství nepřepočítávej.** „Mám to týden“ zapiš jako „k 2026-11-10 asi týden“, ne jako datum začátku.

## Odkaz na rozhovor

Odkaz na vlákno (`vlákno: <název>, <kde>, „<kotva>“`) uveď u rozhodnutí a u pravidel v `jak-pracuju.md`, tedy tam, kde může být později spor o to, co zaznělo. U běžných faktů (lidé, pojmy, mapa, stav práce) stačí datum a zdroj.

Hodiny neznáš, pokud ti je nedal nástroj nebo uživatel. Místo času piš, kde v rozhovoru to bylo: `na začátku`, `asi v polovině`, `ke konci`, `po párování faktur`. Čas nikdy nevymýšlej. Postup je ve `vlakna.md`.

## Oprava a spor

- **Údaj zastaral:** `~~starý údaj~~ (neplatí od RRRR-MM-DD, nahrazeno: …)`.
- **Uživatel řekl nově něco jiného než dřív:** novější výslovný pokyn platí; starý přeškrtni.
- **Změnil se zdrojový soubor:** starý údaj přeškrtni, nový zapiš s datem změny souboru a řekni to uživateli.
- **Dva zdroje stejné váhy si odporují** (dva dokumenty, dokument proti tomu, co řekl uživatel): nech oba, zapiš `SPOR: <co> proti <čemu> (viz otazky.md)` a otázku priority A. Když z dokumentu zapisuješ termín, projdi v něm všechna data a porovnej je s `terminy.md`.
- **Časově omezený údaj** (dovolená, zastupování) po skončení přeškrtni.

## Co kam patří

| Co zaznělo nebo jsi zjistil | Kam |
|---|---|
| Obecné přání, jak pracovat, co nikdy nepsat, jaký formát („nepsat požadujeme“, „DPH vždy zvlášť“) | `jak-pracuju.md` |
| Trvalé pravidlo, které je zároveň rozhodnutí („reklamace nad 20 tisíc vždy i řediteli“) | `jak-pracuju.md`; v `rozhodnuti.md` jen řádek s odkazem |
| Rozhodnutí v jedné věci | `rozhodnuti.md` a stránka práce |
| Jak jednat s konkrétním člověkem (tykání, oslovení, podpis) | `lide.md` u toho člověka |
| Člověk, firma, role, vztah k uživateli (i z dokumentu) | `lide.md`; jen ti, se kterými se pracuje, ne celé seznamy |
| Zkratka, název, pojem | `slovnik.md` |
| Cokoli s datem nebo opakováním, i když to zaznělo jako „zapamatuj si“ | `terminy.md` a stránka práce |
| Úkol uživatele („říct paní Mrázkové…“) | `terminy.md` (s datem, nebo `bez data`) |
| „Zapamatuj si…“ a je jasné, kam to patří | rovnou tam |
| „Zapamatuj si…“ a nevíš, kam to patří | `schranka.md` |
| Stav práce, další krok | `plan.md`, nebo stránka práce, když plán není; v `PREHLED.md` jen jedna věta |
| Co se stalo dnes | `denik/RRRR-MM.md`; u opakovatelné úlohy se štítkem `[úloha: název]` |
| Co kde leží | `mapa-slozek.md` nebo větev |
| Poznatek o tom, jak uživatel používá Clauda | nic; to vede skill `ucitel` |

Jeden údaj má jeden domov. Jinde na něj odkaž, neopisuj ho. Když změníš stav práce nebo termín, který je i v `PREHLED.md`, oprav ho tam hned: přehled čte příští Claude jako první.

Soubor, který ještě neexistuje, založ až při prvním záznamu.
