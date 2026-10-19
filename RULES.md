# Regras da marca — Uniodonto Design System

Sistema de marca e interface da Uniodonto, a primeira cooperativa odontológica do Brasil e do mundo. **A marca carrega os valores do cooperativismo em sua essência**: toda peça assina com o selo SomosCoop. Siga as regras abaixo; tokens em `tokens.json`, classes em `components/bundle.css`, e o brand book completo nas seções Essência da Marca, Assinatura SomosCoop, Marca e Assinaturas, Ingredientes de Linguagem, Aplicações e Linguagem Verbal.

## Antes de qualquer peça

- Parta da essência: **"Unimos experiência e cuidado para transformar sorrisos em todo o Brasil."** Escolha o atributo pelo público — Unidade (cooperados), Experiência (empresas), Otimismo (beneficiários), Relacionamento (comunidade).
- **Assine com o selo SomosCoop em todas as expressões da marca**: num canto, oposto à marca Uniodonto, no máximo 3/4 da largura do logotipo, em branco ou numa cor da paleta (`AssinaturaSomosCoop`). Sem espaço para duas assinaturas, use a assinatura conjunta a 1/2 U. Use os arquivos oficiais de `assets/SomosCoop` (`somoscoop-vinho`, `-roxo`, `-negativo`); nunca redesenhe o selo.
- Peças da operadora levam a tarja ANS (`TarjaANS`), com dados atualizados.

## Conteúdo e tom

- Seja confiável, cuidadoso, acolhedor, simples, alegre, experiente, convidativo e familiar; ajuste ao público (Linguagem Verbal).
- Use "nós" para aproximar do espírito cooperativista e "a Uniodonto" (ela) para afirmar experiência.
- Caixa alta e baixa: maiúscula só na primeira letra das palavras ("Contratar Plano"); nunca títulos inteiros em maiúsculas nem exclamações em série.
- Frases curtas, voz ativa e pessoal: "Cuidamos do seu sorriso".
- Tagline única, sem alterações: *Uniodonto. O nosso sorriso é único.*
- Vocabulário do otimismo: sorriso, alegria, felicidade, tranquilidade, cuidado, leveza, bem-estar, saudável, simplicidade, único.

## Cor

- `uni-vinho-escuro` identifica a instituição e é obrigatória: logotipo institucional, títulos, CTA primário. Os vinhos de apoio (`uni-vinho-medio`, `uni-vinho-ultra`, `uni-vinho-claro`) só aparecem junto dela.
- A paleta vibrante (`uni-roxo`, `uni-pessego`, `uni-ciano`, `uni-lima`, `uni-goiaba`) serve como cor do símbolo, fundo de apoio, forma ou padronagem — nunca substitui o Vinho-Escuro e nunca é cor de texto corrido. `uni-roxo` é a cor oficial das Singulares.
- Fundo claro é sempre `n-0` (branco) ou `bg`/`n-75` (#F3F7FA, azulado). Proibido fundo claro rosado ou avinhado.
- Texto: `text` para corrido, `text-strong` para títulos e labels, `text-muted` para apoio, `text-on-brand` sobre vinhos. `text-muted` sobre `bg` (4,0:1) e `text-subtle` (2,4:1) ficam abaixo de 4,5:1 — use `text-muted` só em texto secundário curto e `text-subtle` só para placeholder.
- Estados: `success`/`success-bg`, `warning`/`warning-bg`, `danger`/`danger-bg`, `info`/`info-bg`; acompanhe sempre a cor com palavra ou ícone.
- Cores `campanha-*` só no período da data comemorativa, e voltam ao padrão logo depois.
- Digital em HEX/RGB; impresso em CMYK/Pantone (`tokens/colors.json`).

## Tipografia

- Georama é a fonte institucional (`--font-brand`, arquivos em `fonts/`). Títulos em Regular; destaque em Itálico no peso oposto. Na manchete, misture regular/light itálico com bold itálico no mesmo bloco ("A nova marca da Uniodonto **carrega os valores do cooperativismo**").
- Texto corrido com entreletra 35 e entrelinha 130% (`body-lg`, `body-md`, `body-sm`).
- Tagline em `tagline` (Georama Itálico) ou `tagline-destaque` (Bold Itálico), entreletra 40.
- Arial só em e-mails e documentos onde Georama não carrega. Caveat (`display-caveat`) só em títulos de peças não institucionais — nunca institucionais. `--font-mono` só para código.

## Espaçamento, raio e elevação

- Use só a escala `s-1`…`s-20` (base 4px). Padding mínimo de card: `s-6`.
- A linguagem é arredondada como o "U": `r-lg` em botões, `r-md` em inputs, `r-sm` em badges, `r-xl` em cards, `r-full` em pílulas e tags (`pill-tag`). Fotos e mockups sempre em recorte arredondado, nunca em retângulo reto.
- Sombras discretas e frias. Foco visível com `sh-ring-focus` (roxo) somado à troca de borda para `uni-vinho-escuro`.

## Componentes

- `btn primary` (Vinho-Escuro, texto bold itálico): um por tela. `btn secondary`, `btn tertiary`, `btn accent` (Lima, só não institucional), `btn danger`.
- Formulários: `field` com `label` bold itálico sempre visível, `input`, `hint` e `error` específicos.
- `badge`, `card`, `tabs-list`/`tab-trigger`, `check-row`/`cbox`, `pill-tag` (etiqueta de contorno vinho) e `quick-card` (Acesso Rápido do portal, ícone simplificado sempre com descritivo).
- Marca: `AssinaturaSomosCoop` (proporção, posição e assinatura conjunta) e `TarjaANS`.

## Marca, padronagens, formas e imagem

- Logotipos oficiais em `assets/Logos` (horizontal, vertical, só logotipo; positivo e negativo; símbolo em cada cor), símbolo em `assets/Simbolo`. Área de proteção = altura do "U". Sem distorção, rotação, sombra, contorno ou gradiente.
- Padronagens (`assets/Padronagens`): estilo 1 (arcada de U e U invertido) e estilo 2 (anéis de U); institucional sempre com vinho presente.
- Formas (`assets/Formas`): squircle, trapézio em U e pílula, como boxes, molduras e abas.
- Ícones em `assets/Icones`: destaque (cor vibrante + contorno vinho), simplificados (web, sempre com descritivo), serviços (dente em linha vinho). Sem emoji.
- Fotografia: alegria, espontaneidade, naturalidade e diversidade; recortes sobre cor vibrante com padronagem de U, ou ambiente com luz natural.
