# Mozek

Osobní paměť na vašem počítači a nenásilný učitel práce s Claudem. Plugin pro Claude Desktop (Cowork) a claude.ai od AI Stack.

Claude si ve složce obyčejných textových souborů vede, na čem pracujete, kdo je kdo, co se rozhodlo a co ještě neví. Čím víc s ním pracujete, tím míň mu musíte vysvětlovat. Jednou za 14 dní navrhne dvě až tři věci, které můžete s Claudem zkusit dál.

Plugin obsahuje jen textové instrukce. Na vašem počítači nic nespouští a celý jeho obsah si můžete přečíst v této složce.

## Nastavení

1. V aplikaci Claude otevřete Customize, Plugins, Add, Add marketplace, vložte `mjanostik-spec/aistack-pluginy`, zapněte Sync automatically a přidejte plugin Mozek.
2. V Dokumentech vytvořte složku `Claude-mozek`. V Coworku založte projekt, vyberte svou pracovní složku a přidejte k ní složku `Claude-mozek`.
3. Napište `/mozek:start` a odpovězte na pár otázek.

Potřebujete placený plán Clauda (Pro, Max, Ultra, Team nebo Enterprise).

## Příkazy

| Příkaz | Co udělá |
|---|---|
| `/mozek:start` | Úvodní rozhovor a založení paměti. |
| `/mozek:co-vis` | Ukáže, co si o vás Claude pamatuje, a nechá vás to opravit. |
| `/mozek:ohlednuti` | Týdenní ohlédnutí: co se udělalo, otázky, úklid. |
| `/mozek:tip` | Jedna věc, kterou můžete zkusit dál. |
| `/mozek:zastaveni` | Čtrnáctidenní zastavení s učitelem. |

Kdykoli můžete říct „zapamatuj si…“, „míň tipů“, „tipy nechci“ nebo „učitele vypni“.

## Vaše data

Paměť leží jen ve složce `Claude-mozek` na vašem počítači. Plugin nic neposílá AI Stack ani nikomu dalšímu. Obsah souborů, se kterými Claude pracuje, zpracovává Anthropic stejně jako každý rozhovor s Claudem; na plánech Pro, Max a Ultra doporučujeme v nastavení vypnout použití rozhovorů k trénování modelů.

Hesla, rodná čísla, mzdy a zdravotní údaje si Claude podle pravidel pluginu nezapisuje. Složku si můžete kdykoli otevřít, upravit nebo smazat.

## Stav

Verze 0.1.0, zkušební. Postaveno podle dokumentace, v provozu zatím neověřeno.
