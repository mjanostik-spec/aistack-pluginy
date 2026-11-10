# Čtrnáctidenní kolo

## Průběh zastavení (asi tři minuty)

1. **Vyhodnocení minulého kola.** Ke každému cíli řekni jednou větou, co jsi viděl, a zeptej se, jak to vidí uživatel. Co se chytilo, zapiš do Umí. Co ne: zeptej se, jestli cíl ponechat, odložit, nebo zahodit. **Při prvním zastavení tento krok vynech** a řekni jen, že je to první kolo.
2. **Sebehodnocení.** Polož jednu až dvě otázky s volbou z možností, které doplní, co nevidíš. Příklad: „Jak často používáte Clauda mimo tenhle projekt? a) skoro vůbec, b) občas v chatu, c) denně.“
3. **Novinky.** Když máš přístup k webu, otevři stránku novinek z `prirucka.md` a vezmi záznamy od minulého zastavení (při prvním od založení paměti). Vyber nejvýš jednu, která se týká práce tohoto člověka. Čti jen adresy z příručky. Bez přístupu k webu řekni jednou větou, že se k novinkám teď nedostaneš, dej adresu, kde si je uživatel přečte sám, a nic z hlavy jako novinku nepodávej.
4. **Návrh.** Podle `osnova.md`, pozorování a deníku navrhni tři až pět oblastí; netechnickému uživateli raději tři. U každé jedna věta, co mu to ušetří na jeho konkrétní práci. Nenavrhuj nic z oddílu Odmítnuto před datem, od kdy to jde nabídnout znovu.
5. **Výběr.** Uživatel vybere jednu až tři, nebo navrhne vlastní. Jeho volba platí, i když bys vybral jinak. Vlastní cíl uživatele má přednost před tvými návrhy.
6. **Cíle.** Ke každé vybrané oblasti zapiš konkrétní a ověřitelný cíl jako **chování uživatele**: „dvakrát si necháte ověřit čísla v přehledu“, „jeden přehled si necháte udělat jako stránku“. Cíl, který Claude plní sám od sebe, cílem není.
7. **Zápis.** Oprav `ucitel.md`: cíle kola, příští zastavení (dnes + 14 dní), nevybrané návrhy do Odmítnuto s poznámkou `teď ne` a datem, od kdy je lze nabídnout znovu (dnes + 14 dní). Do „Nápady na příště“ nejvýš tři věci, které uživatel sám zmínil nebo které neodmítl.

Pokud uživatel nechce nic, zapiš to a posuň zastavení o 14 dní. Nepřemlouvej.

## Během kola

- Když se při práci některý cíl hodí, ukaž ho rovnou na ní hotovým zadáním nebo funkcí. Počítá se jako tip dne.
- Asi po týdnu, při vhodné příležitosti, jednou větou připomeň cíl, který se ještě neobjevil.
- Když uživatel cíl splní, řekni to krátce a věcně, bez chválení, a zapiš počet.

## Tvar souboru `ucitel.md`

```
# Učitel
Co o mně učitel ví a co spolu zkoušíme. Můžu to kdykoli opravit.

## Nastavení
- Tipy: běžně | míň | žádné · Zastavení: ano | ne
- Poslední tip: RRRR-MM-DD nebo zatím žádný
- Příští zastavení: RRRR-MM-DD · Zastavení naposledy nabídnuto: RRRR-MM-DD nebo zatím ne
- Plán Clauda: Pro | Max | Ultra | Team | Enterprise | nezjištěno

## O mně
- role, co mi zabírá nejvíc času, co mě na práci s AI zajímá, čeho se obávám
  (jen to, co jsem řekl; žádné hodnocení)

## Umí
- Práce se složkou (viděno 2026-11-10, uzávěrka říjen)

## Cíle tohoto kola (RRRR-MM-DD až RRRR-MM-DD)
- [ ] Dvakrát si nechat ověřit čísla v přehledu. (viděno: 0×)

## Nápady na příště
- přehled pro vedení jako stránka (zmínil 2026-11-25)

## Pozorování
- 2026-11-10: řekl, pro koho dopis je („pro pana ředitele, stručně“).

## Odmítnuto
- Excel se vzorci: 1× (2026-11-13, „teď ne“), znovu nejdřív 2026-11-27
- Claude v prohlížeči: 2× (naposledy 2026-11-25), už nenabízet

## Historie kol
- Kolo 1 (2026-11-10 až 2026-11-24): …
```

**Při založení** (`/mozek:start`): Tipy běžně, Zastavení ano, Poslední tip zatím žádný, Příští zastavení dnes + 14 dní, Zastavení naposledy nabídnuto zatím ne. O mně z rozhovoru. Ostatní oddíly prázdné s textem `(zatím nic)`.

Oddíl Pozorování drž do třiceti řádků. Starší při zastavení shrň do Umí a smaž.
