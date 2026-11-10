# Příručka učitele

Rozcestník k funkcím Clauda. Udržuje AI Stack, poslední kontrola adres 2026-11-10. Claude se mění každý týden: než funkci doporučíš, ověř ji na odkazu, hlavně název v aplikaci a dostupnost na plánu uživatele. Když se příručka a dokumentace liší, platí dokumentace.

Čti jen tyto čtyři weby. Jiné stránky kvůli učení neotvírej.

## Zdroje

| Zdroj | Adresa | K čemu |
|---|---|---|
| Dokumentace | https://claude.com/docs/llms.txt | Rejstřík asi 500 stránek. Najdi stránku podle názvu funkce a otevři ji. |
| Nápověda | https://support.claude.com | Návody pro uživatele: projekty, artefakty, paměť, plány a ceny. |
| Novinky | https://support.claude.com/en/articles/12138966-release-notes | Co je nového, několik záznamů měsíčně. |
| Změny Coworku a aplikace | https://claude.com/docs/cowork/changelog.md | Co se změnilo v Coworku a v aplikaci pro počítač. |
| Kurzy Anthropicu | https://anthropic.skilljar.com | Pro toho, kdo chce víc. Anglicky. |
| Dokumentace Claude Code | https://code.claude.com/docs | Jen pro poslední příčku žebříčku. |

## Funkce

| Funkce | Co uživateli ušetří | Kde číst |
|---|---|---|
| Cowork: práce se složkou | Claude čte a ukládá soubory přímo ve složce, nic se nenahrává ručně. | https://claude.com/docs/cowork/overview.md |
| Hotové soubory | Excel se vzorci, Word, prezentace jako výsledek, ne text ke kopírování. | https://claude.com/docs/cowork/overview.md |
| Projekty | Oblast práce má vlastní složky, pokyny a paměť, nic se nemíchá. | https://claude.com/docs/cowork/guide/projects.md |
| Artefakty | Přehled nebo nástroj jako stránka, která jde otevřít, upravit a poslat dál. | nápověda, hledej „artifacts“ |
| Konektory | Claude pracuje s poštou, kalendářem, diskem a dalšími službami. | https://claude.com/docs/connectors/getting-started.md |
| Skilly | Opakovaný postup, který Claude použije sám, když se hodí. | https://claude.com/docs/skills/overview.md |
| Pluginy | Sada skillů a příkazů pro jednu roli nebo firmu. | https://claude.com/docs/plugins/overview.md |
| Plánované úlohy | Pravidelná práce bez zadávání. Pozor: úloha v cloudu nedosáhne na místní složky. | rejstřík dokumentace, hledej „scheduled“ |
| Hledání v rozhovorech a paměť | Claude najde, co se řešilo dřív. Hledá uvnitř projektu. | https://support.claude.com/en/articles/11817273-use-claude-s-chat-search-and-memory-to-build-on-previous-context |
| Claude v prohlížeči | Úlohy na webových stránkách bez konektoru. | https://claude.com/chrome |
| Vlastní plugin rozhovorem | Uživatel si sadu postupů vyrobí sám a sdílí ji kolegům. | https://claude.com/docs/plugins/create-with-claude.md |

## Plány (stav 2026-11-10)

- Free: bez Coworku, skillů a pluginů.
- Pro, Max, Ultra: Cowork, skilly, pluginy, konektory, hledání v rozhovorech.
- Team, Enterprise: navíc sdílení pluginů v organizaci a pluginy povinné pro všechny.

Před doporučením funkce, která závisí na plánu, se podívej do `ucitel.md`, jaký plán uživatel má. Když to tam není, zeptej se.

## Kurzy

| Kurz | Pro koho | Adresa |
|---|---|---|
| Claude 101 | Úplný začátek. | https://anthropic.skilljar.com/claude-101 |
| Introduction to Claude Cowork | Kdo začíná s Coworkem. | https://anthropic.skilljar.com/introduction-to-claude-cowork |
| AI Fluency: Framework & Foundations | Kdo chce rozumět tomu, jak s AI spolupracovat. | https://anthropic.skilljar.com/ai-fluency-framework-foundations |
| AI Fluency for Small Businesses | Majitelé a lidé z malých firem. | https://anthropic.skilljar.com/ai-fluency-for-small-businesses |

Kurz nabídni jen tomu, kdo řekne, že chce víc. Jinak uč na jeho práci.

## Co platí při práci s Coworkem

- Na plánech Pro, Max a Ultra běží Cowork na serverech Anthropicu a ke složkám na počítači se dostává přes zapnutou aplikaci. Když je aplikace zavřená, na složky nedosáhne.
- Obsah souborů, se kterými Claude pracuje, jde ke zpracování do cloudu. U citlivých dokumentů na to uživatele upozorni.
- Do projektu patří úzká pracovní složka, ne celé Dokumenty.
