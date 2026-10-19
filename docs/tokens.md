# Tokens

Every token of the system, a section per group: Surfaces — 3 tokens; Text — 5 tokens; Borders and rings — 3 tokens; Palette ramps and brand — 37 tokens; Type styles, families, font files; Spacing — 11 tokens; Radius — 8 tokens; Shadow — 10 tokens.

## Color · Surfaces

### Use

```css
/* any surface that loads tokens.css or components/bundle.css */
color: var(--surface);
/* a surface with no stylesheet (a slide): the light value */
```

### Tokens (3)

| token | light | usage |
| --- | --- | --- |
| `surface` | #ffffff | Cards, inputs, botão secundário. |
| `surface-muted` | #f3f7fa | Hover de botões tertiary/secondary, badge `neutral`, input desabilitado. |
| `surface-inset` | #e8eef3 | Active do botão secundário, áreas rebaixadas. |

## Color · Text

### Use

```css
/* any surface that loads tokens.css or components/bundle.css */
color: var(--text);
/* a surface with no stylesheet (a slide): the light value */
```

### Tokens (5)

| token | light | usage |
| --- | --- | --- |
| `text` | #232c34 | Texto corrido sobre `bg` e `surface` (13:1+). |
| `text-strong` | #550039 | Títulos, labels e texto de ênfase sobre `bg` e `surface` (13,5:1). |
| `text-muted` | #6b7c8a | Texto secundário, hints, abas inativas sobre `surface` (4,3:1) e `bg` (4,0:1 — abaixo de 4,5:1; valor da fonte mantido, use só em 14px+ semibold ou 24px+ sobre `bg`). |
| `text-subtle` | #98a9b7 | Placeholder e texto desabilitado sobre `surface` — 2,4:1, abaixo do mínimo de texto; valor da fonte mantido. |
| `text-on-brand` | #ffffff | Texto sobre `uni-vinho-escuro` (9,9:1) e demais vinhos. |

## Color · Borders and rings

### Use

```css
/* any surface that loads tokens.css or components/bundle.css */
color: var(--border);
/* a surface with no stylesheet (a slide): the light value */
```

### Tokens (3)

| token | light | usage |
| --- | --- | --- |
| `border` | #e8eef3 | Divisórias, borda de card, lista de abas. |
| `border-strong` | #dbe4eb | Borda de controles (input, botão secundário). |

**Interaction states** (same roles, suffixed):

| token | light |
| --- | --- |
| `border-focus` | #bf9cff |

## Color · Palette ramps and brand

### Use

```css
/* any surface that loads tokens.css or components/bundle.css */
color: var(--uni-vinho-escuro);
/* a surface with no stylesheet (a slide): the light value */
```

### Tokens (37)

| token | light | usage |
| --- | --- | --- |
| `uni-vinho-escuro` | #810e56 | Vinho-Escuro Uniodonto (Pantone 242 C) — cor oficial e obrigatória da marca: logotipo institucional, títulos, CTA primário (`btn primary`), sublinhado da aba ativa. Branco sobre ela: 9,9:1; sobre `n-75`: 9,2:1. |
| `uni-vinho-medio` | #a60069 | Vinho Médio (Pantone 234 C) — variação tonal; hover do botão primário. Combinar sempre com Vinho-Escuro. |
| `uni-vinho-ultra` | #550039 | Vinho Ultra (Pantone 229 C) — fundos escuros institucionais, active do primário, texto forte (`text-strong`) e texto sobre cores complementares. |
| `uni-vinho-claro` | #bc5688 | Vinho-Claro (Pantone 674 C) — acentos suaves e gráficos secundários; não usar como cor de texto. |
| `uni-preto` | #121212 | Marca monocromática PB — só quando cor é impossível. (tokens/colors.json registra Preto como #111111; o stylesheet usa #121212.) |
| `uni-roxo` | #bf9cff | Roxo Uniodonto (Pantone 2572 C) — cor oficial das Singulares; anel de foco (`border-focus`, `sh-ring-focus`); badge `roxo`. Contraste 2,2:1 sobre branco: nunca como texto, e o anel de foco fica abaixo de 3:1 (valor da fonte mantido). |
| `uni-pessego` | #ff9fad | Pêssego Uniodonto (Pantone 1765 C) — acolhimento, campanhas, ilustrações; fundo de apoio, nunca texto. |
| `uni-ciano` | #60ebff | Ciano Uniodonto (Pantone 310 C) — frescor, conteúdos educativos, elementos digitais; fundo de apoio, nunca texto. |
| `uni-lima` | #e1ff7b | Lima Uniodonto (Pantone 379 C) — alegria, prevenção; fundo do botão `accent` com texto `uni-vinho-ultra` (13:1). |
| `uni-goiaba` | #ff637e | Goiaba Uniodonto (Pantone 184 C) — energia, CTAs não-institucionais, campanhas; badge `goiaba`. |
| `bg` | #f3f7fa | Fundo da página. |
| `success` | #1f7a4c | Texto/ícone de sucesso sobre `success-bg` (4,7:1) e `surface`. |
| `success-bg` | #e6f3eb | Fundo do badge `success`. |
| `warning` | #b45b0e | Texto de pendência sobre `warning-bg` — 4,1:1, abaixo de 4,5:1; valor da fonte mantido. |
| `warning-bg` | #fbecd8 | Fundo do badge `warning`. |
| `danger` | #b3261e | Erro, ação destrutiva: texto sobre `danger-bg` (5,4:1) e `surface`; borda de input inválido. |
| `danger-bg` | #fbe4e2 | Fundo do badge `danger` e hover do botão `danger`. |
| `info` | #1f6faf | Texto informativo sobre `info-bg` (4,5:1). |
| `info-bg` | #e2eef8 | Fundo do badge `info`. |
| `brand-soft` | #f7d9e8 | `surface.brandSoft` de tokens/colors.json — item selecionado do Select. |
| `campanha-outubro-rosa` | #ff4da6 | Outubro Rosa — uso restrito ao mês 10. |
| `campanha-novembro-azul` | #1e6fd9 | Novembro Azul — uso restrito ao mês 11. |
| `campanha-setembro-amarelo` | #f5c518 | Setembro Amarelo — uso restrito ao mês 09. |
| `campanha-verde-brasil` | #00a859 | Verde Brasil — datas nacionais (09/11). |

| ramp | steps | first → last (light) |
| --- | --- | --- |
| `n-*` | 0, 50, 75, 100, 150, 200, 300, 400, 500, 600, 700, 800, 900 | #ffffff → #0b1013 |

## Type

Use the named styles; no literal px.

### Use

```css
font: var(--text-display-xl);            /* with tokens.css */
font-family: var(--font-brand);   /* the family alone */
```

### Styles

| style | CSS | size / line | weight | family | usage |
| --- | --- | --- | --- | --- | --- |
| `display-xl` | `.display-xl`, `--text-display-xl` | 80px / 1.05 | 500 | `brand` | Heros, aberturas de campanha |
| `display-lg` | `.display-lg`, `--text-display-lg` | 64px / 1.1 | 500 | `brand` | Headlines de landing |
| `display-md` | `.display-md`, `--text-display-md` | 48px / 1.15 | 500 | `brand` | Headlines secundários |
| `heading-1` | `.heading-1`, `--text-heading-1` | 36px / 1.2 | 600 | `brand` | Título de página |
| `heading-2` | `.heading-2`, `--text-heading-2` | 28px / 1.25 | 600 | `brand` | Seções |
| `heading-3` | `.heading-3`, `--text-heading-3` | 22px / 1.3 | 600 | `brand` | Subseções, cards |
| `heading-4` | `.heading-4`, `--text-heading-4` | 18px / 1.35 | 600 | `brand` | Títulos inline |
| `body-lg` | `.body-lg`, `--text-body-lg` | 18px / 1.55 | 400 | `brand` | Parágrafos de destaque |
| `body-md` | `.body-md`, `--text-body-md` | 16px / 1.55 | 400 | `brand` | Texto padrão |
| `body-sm` | `.body-sm`, `--text-body-sm` | 14px / 1.5 | 400 | `brand` | Legendas, metadados |
| `caption` | `.caption`, `--text-caption` | 12px / 1.4 | 500 | `brand` | Microcopy, labels |
| `overline` | `.overline`, `--text-overline` | 11px / 1.4 | 600 | `brand` | Rótulos de seção (Title Case) |

### Families

| family | CSS variable | stack |
| --- | --- | --- |
| `brand` | `--font-brand` | `'Georama', 'Inter', system-ui, -apple-system, sans-serif` |
| `mono` | `--font-mono` | `'JetBrains Mono', ui-monospace, 'SF Mono', monospace` |

### Font files

Fonts: `tokens.css` loads each font from its file, by path.

- **Design canvas:** copy `tokens.css`, `fonts/Georama-VariableFont_wdth_wght.ttf` and `fonts/Georama-Italic-VariableFont_wdth_wght.ttf` to the same paths under the canvas’s `project/ds/<folder>/` (`<folder>` is the folder you install this system under; `fonts/Georama-VariableFont_wdth_wght.ttf` lands on `project/ds/<folder>/fonts/Georama-VariableFont_wdth_wght.ttf`), in the same call that installs this system. Link that copy of `tokens.css` in the artboard’s `<head>` as `ds/<folder>/tokens.css`, or as Design’s instructions say for an artboard in a folder. If the install’s reply leaves a font out, bring that font in as for any other page.
- **Slides deck:** for each family you use in the deck (`faces` holds at most the number of typefaces Slides’ `deck-files.md` gives), install its file with the system and name the path it lands on as that family’s `src` in `project/deck.json` `faces`, under the key in the Slides column. A deck takes a font as a file only under the rule in Slides’ `fonts.md` (no space or leading underscore in its path, for two): any other font, or one kept by id, is uploaded as `fonts.md` says.
- **Any other page:** one file per family is enough (below: the upright face nearest regular weight; bold and italic synthesize). Fetch it as the fetch column says (Artifact tool `read`, that id or path as `path`), upload it as an asset (`publish`, `file_path`, `asset:true`) and declare it with an `@font-face { font-family: "<family>"; src: url(<uploaded>) }` rule.

`tokens.css` carries the `@font-face` rules for a page that links it and names each family by the CSS variable below.

| family | file | fetch | CSS | Slides `faces` key |
| --- | --- | --- | --- | --- |
| Georama | `fonts/Georama-VariableFont_wdth_wght.ttf` (weight 100 900) | `read` the file with `project/` in front | `var(--font-brand)` | `georama` |

Every face: `fonts/Georama-VariableFont_wdth_wght.ttf` (Georama, 100 900), `fonts/Georama-Italic-VariableFont_wdth_wght.ttf` (Georama, 100 900, italic).

## Spacing

### Use

```css
padding: var(--s-1);
```

### Tokens (11)

| token | value | usage |
| --- | --- | --- |
| `s-1` | 4px | Gap mínimo. |
| `s-2` | 8px | Gap entre ícone e texto, badges. |
| `s-3` | 12px | Padding horizontal de input. |
| `s-4` | 16px | Gap padrão entre elementos. |
| `s-5` | 20px | Padding horizontal do botão lg. |
| `s-6` | 24px | Padding interno mínimo de card. |
| `s-8` | 32px | Espaço entre grupos. |
| `s-10` | 40px | Seções compactas. |
| `s-12` | 48px | Seções de página. |
| `s-16` | 64px | Seções grandes. |
| `s-20` | 80px | Heros. |

## Radius

### Use

```css
/* var(--r-xs) */
```

### Tokens (8)

| token | value | usage |
| --- | --- | --- |
| `r-xs` | 4px | Checkbox. |
| `r-sm` | 6px | Badge, topo das abas, linha de checkbox. |
| `r-md` | 8px | Botões, inputs, busca. |
| `r-lg` | 12px | Blocos médios. |
| `r-xl` | 16px | Card. |
| `r-2xl` | 20px | Painéis grandes. |
| `r-3xl` | 28px | Hero, mockups. |
| `r-full` | 9999px | Pílulas e chips — nunca em botão retangular padrão. |

## Shadow

### Use

```css
/* var(--sh-xs) */
```

### Tokens (10)

| token | value | usage |
| --- | --- | --- |
| `sh-xs` | 0 1px 2px rgba(35, 44, 52, 0.05) | Botão secundário, input. |
| `sh-sm` | 0 1px 2px rgba(35, 44, 52, 0.06), 0 1px 3px rgba(35, 44, 52, 0.05) | Elevação leve. |
| `sh-md` | 0 2px 4px rgba(35, 44, 52, 0.04), 0 6px 16px rgba(35, 44, 52, 0.07) | Card em hover, popover do Select. |
| `sh-lg` | 0 4px 8px rgba(35, 44, 52, 0.05), 0 16px 32px rgba(35, 44, 52, 0.10) | Menus e painéis flutuantes. |
| `sh-xl` | 0 8px 16px rgba(35, 44, 52, 0.06), 0 24px 60px rgba(35, 44, 52, 0.14) | Modais. |
| `sh-inset` | inset 0 0 0 1px rgba(255,255,255,0.08) | Brilho interno sobre fundos escuros. |
| `sh-ring-brand` | 0 0 0 3px rgba(129, 14, 86, 0.15) | Anel de seleção vinho. |
| `sh-ring-focus` | 0 0 0 3px rgba(191, 156, 255, 0.50) | Foco visível de botões e inputs (roxo). |
| `sh-ring-danger` | 0 0 0 3px rgba(179, 38, 30, 0.18) | Foco de input inválido. |
| `sh-ring-success` | 0 0 0 3px rgba(31, 122, 76, 0.18) | Foco de input válido. |
