# Příručka učitele

Rozcestník k funkcím Clauda. Udržuje AI Stack. **Stav k 2026-11-11.** Claude se mění každý týden: když máš přístup k webu, ověř funkci na odkazu, než ji doporučíš. Když se příručka a dokumentace liší, platí dokumentace.

Bez přístupu k webu smíš doporučit jen funkci z tabulky níže, která je na plánu uživatele, a řekni: „podle příručky k 11. 11. 2026“. Přesné názvy tlačítek z hlavy neuváděj; popiš, co hledat, a nech uživatele říct, co vidí.

Čti jen weby z tabulky Zdroje. Jiné stránky kvůli učení neotvírej.

## Zdroje

| Zdroj | Adresa | K čemu |
|---|---|---|
| Dokumentace | https://claude.com/docs/llms.txt | Rejstřík stránek. Najdi stránku podle názvu funkce a otevři ji. |
| Nápověda | https://support.claude.com | Návody pro uživatele: projekty, artefakty, paměť, plány a ceny, ochrana dat. |
| Novinky | https://support.claude.com/en/articles/12138966-release-notes | Co je nového, několik záznamů měsíčně. |
| Změny Coworku a aplikace | https://claude.com/docs/cowork/changelog.md | Co se změnilo v Coworku a v aplikaci pro počítač. |
| Kurzy Anthropicu | https://anthropic.skilljar.com | Pro toho, kdo chce víc. Anglicky. |
| Dokumentace Claude Code | https://code.claude.com/docs | Jen pro poslední příčku žebříčku. |

## Funkce

Všechny funkce v tabulce jsou podle dokumentace dostupné na placených plánech (Pro, Max, Ultra, Team, Enterprise). Na Team a Enterprise může konektory a pluginy povolovat správce účtu firmy.

| Funkce | Co uživateli ušetří | Kde ji hledat v aplikaci | Kde číst |
|---|---|---|---|
| Cowork: práce se složkou | Claude čte a ukládá soubory přímo ve složce. | záložka Cowork | https://claude.com/docs/cowork/overview.md |
| Hotové soubory | Excel se vzorci, Word, prezentace, PDF jako výsledek. | stačí o ně říct | https://claude.com/docs/cowork/overview.md |
| Projekty | Oblast práce má vlastní složky a pokyny. | vlevo Projects, tlačítko + | https://claude.com/docs/cowork/guide/projects.md |
| Artefakty (stránka nebo nástroj) | Přehled či kalkulačka, kterou jde otevřít, upravit větou a poslat dál. | stačí říct „udělej to jako stránku“ | https://support.claude.com (hledej „artifacts“) |
| Konektory | Claude pracuje s poštou, kalendářem, diskem. | Customize, Connectors; v rozhovoru zapnout přes + | https://claude.com/docs/connectors/getting-started.md |
| Skilly | Opakovaný postup, který Claude použije sám. | Customize, Skills | https://claude.com/docs/skills/overview.md |
| Pluginy | Sada skillů a příkazů pro roli nebo firmu. | Customize, Plugins | https://claude.com/docs/plugins/overview.md |
| Plánované úlohy | Pravidelná práce bez zadávání. | ověř v dokumentaci, hledej „scheduled“ | https://claude.com/docs/llms.txt |
| Hledání v rozhovorech | Claude najde, co se řešilo dřív; hledá uvnitř projektu. | stačí se zeptat | https://support.claude.com/en/articles/11817273-use-claude-s-chat-search-and-memory-to-build-on-previous-context |
| Claude v prohlížeči | Úlohy na webových stránkách bez konektoru. | rozšíření pro Chrome | https://claude.com/chrome |
| Zadání na dálku (Dispatch) | Práce zadaná z telefonu, výsledek čeká na počítači. | ověř v dokumentaci | https://claude.com/docs/cowork/guide/dispatch.md |
| Vlastní plugin rozhovorem | Sada postupů vyrobená rozhovorem a sdílená kolegům. | Customize, Plugins, Add | https://claude.com/docs/plugins/create-with-claude.md |

Poznámky ověřené zkušeností AI Stack:
- Gmail konektor umí e-mail i odeslat (vyzkoušeno 2026-11-11), i když dokumentace uvádí jen čtení. Doporuč nechat u odesílání potvrzování zapnuté.
- Když artefakt v daném prostředí vytvořit nejde, ulož přehled jako jeden samostatný soubor HTML do pracovní složky a řekni, že se otevře dvojklikem v prohlížeči.

## Co platí o souborech a cloudu

- Na plánech Pro, Max a Ultra běží Cowork na serverech Anthropicu a ke složkám v počítači se dostává přes zapnutou aplikaci. Když je aplikace zavřená nebo počítač spí, na složky nedosáhne.
- **Plánovaná úloha, která běží v cloudu, na složky v počítači nedosáhne vůbec.** Hodí se na práci s konektory (pošta, kalendář). Na otázku, jestli úloha poběží nad místní složkou, odpověz, že podle dokumentace ne, a nabídni ověření na odkazu.
- Obsah souborů, se kterými Claude pracuje, zpracovává Anthropic. Na plánech Pro, Max a Ultra si uživatel může v nastavení (Privacy) vypnout použití rozhovorů k trénování. Na Team a Enterprise platí smlouva firmy; přesné podmínky potvrdí správce účtu. Nic dalšího o ochraně dat netvrď.
- Do projektu patří úzká pracovní složka, ne celé Dokumenty.

## Kurzy

| Kurz | Pro koho | Adresa |
|---|---|---|
| Claude 101 | Úplný začátek. | https://anthropic.skilljar.com/claude-101 |
| Introduction to Claude Cowork | Kdo začíná s Coworkem. | https://anthropic.skilljar.com/introduction-to-claude-cowork |
| AI Fluency: Framework & Foundations | Kdo chce rozumět spolupráci s AI. | https://anthropic.skilljar.com/ai-fluency-framework-foundations |
| AI Fluency for Small Businesses | Majitelé a lidé z malých firem. | https://anthropic.skilljar.com/ai-fluency-for-small-businesses |

Kurz nabídni jen tomu, kdo řekne, že chce víc. Jinak uč na jeho práci.
