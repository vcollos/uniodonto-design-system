# Uniodonto Design System

Tokens, regras do brand book e arquivos oficiais da marca **Uniodonto**, prontos para pessoas e agentes de IA (Codex, ChatGPT, Claude, Gemini, Cursor…).

- **Página:** https://designsystem.uniodonto.coop.br
- **Para agentes:** comece por [`AGENTS.md`](AGENTS.md). Índice para LLMs: [`llms.txt`](llms.txt) · texto completo: [`llms-full.txt`](llms-full.txt)
- **Regras resumidas:** [`RULES.md`](RULES.md) · **Brand book:** [`brandbook/`](brandbook)
- **Tokens:** [`tokens.json`](tokens.json) · [`tokens.css`](tokens.css) · tabela em [`docs/tokens.md`](docs/tokens.md)
- **Assets:** [`assets/`](assets) — logos, símbolo, selo SomosCoop, submarcas, template das Singulares, ícones, formas, padronagens

## Uso rápido

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/vcollos/uniodonto-design-system@main/tokens.css">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/vcollos/uniodonto-design-system@main/components/bundle.css">
```

Para um agente sem acesso ao repositório, cole no prompt:

```
Siga o Uniodonto Design System: https://raw.githubusercontent.com/vcollos/uniodonto-design-system/main/AGENTS.md
Use só os tokens e os arquivos oficiais listados em https://raw.githubusercontent.com/vcollos/uniodonto-design-system/main/llms.txt
```

## Origem

Mantido no Claude (artefato "Uniodonto Design System") e espelhado aqui. A fonte Georama é OFL 1.1 (`fonts/README.md`). Marcas e logotipos são propriedade da Uniodonto do Brasil: use-os somente em materiais da Uniodonto e das Singulares.
