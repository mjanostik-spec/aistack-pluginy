# Pluginy AI Stack pro Claude

Tržiště pluginů od [AI Stack](https://aistack.cz) pro Claude Desktop (Cowork), claude.ai a Claude Code.

| Plugin | Co dělá |
|---|---|
| [Mozek](mozek/README.md) | Osobní paměť na vašem počítači a nenásilný učitel práce s Claudem. |

## Přidání

V aplikaci Claude: Customize, Plugins, Add, Add marketplace, vložte `mjanostik-spec/aistack-pluginy` a zapněte Sync automatically. Nové verze pak přicházejí samy.

## Pro správce repa

- Do repa nepatří nic o klientech, žádná jména, adresy ani tajemství. Repo je veřejné.
- Každá změna v `main` dojde všem uživatelům bez potvrzení. Měň jen přes kontrolovanou změnu a po přečtení celého rozdílu.
- Při každém vydání zvedni `version` v `mozek/.claude-plugin/plugin.json`.
- Příručku učitele (`mozek/skills/ucitel/references/prirucka.md`) kontroluj proti dokumentaci a novinkám Anthropicu a opravuj v ní datum kontroly.
- Kontrola před vydáním: `claude plugin validate ./mozek`.

© AI Stack (aistack.cz). Podmínky použití v souboru LICENSE.
