# Marca e Assinaturas

A marca nasce do olhar no detalhe do sorriso: as letras foram desenhadas a partir do formato dos dentes, criando um elemento modular — o "U" — capaz de ser singular e plural. Use sempre os arquivos digitais fornecidos (`assets/Logos`, `assets/Simbolo`); nunca redesenhe.

- **Logotipo (A):** a palavra "uniodonto", em minúsculas.
- **Símbolo (B):** círculo sólido com o "U" vazado — "uma parte do todo que compõe o sorriso".

## Arquitetura de marcas

A Uniodonto segue a arquitetura **monolítica**: as marcas endossadas obedecem aos mesmos padrões de aplicação e linguagem.

- **Uniodonto Brasil** — a marca-mãe, institucional.
- **Uniodonto Singular** — cada cooperativa local; símbolo e nome em `uni-roxo`.
- **Soluções Uniodonto** — submarcas com assinatura própria: Banco U (fintech), Dental U (loja; endosso "uniodonto"), Mobile, RXScan, Sig U (software de gestão, ciano), UCX, U Fast (app de intercâmbio, goiaba), U Hub e U Rede. Arquivos em `assets/Submarcas`.
- **Modalidades de atendimento** — sem marca, só o descritivo com ícone de apoio: Plantão 24h, Teleodontologia, Unidade Móvel, Central de Vendas, App Mobile.
- **Segmentos** — "uniodonto" + descritor (express, preventiva).

## Versões

| Versão | Logotipo | Símbolo | Fundo | Uso |
| --- | --- | --- | --- | --- |
| Positiva institucional | `uni-vinho-escuro` | `uni-vinho-escuro` | Branco ou cores complementares | Preferencial em materiais institucionais |
| Negativa institucional | Branco | Branco | Variações de vinho | Institucional sobre fundo escuro |
| Positiva não institucional | `uni-vinho-escuro` | Roxo, Pêssego, Ciano, Lima ou Goiaba | Branco | Campanhas, anúncios, filmes |
| Negativa não institucional | Branco | Roxo, Pêssego, Ciano, Lima ou Goiaba | Variações de vinho | Campanhas sobre vinho |
| Monocromática | `uni-preto` (#121212) ou branco | Idem | Branco ou preto | Só quando a reprodução é de uma cor |

- Sobre fundo de cor complementar, use a versão positiva (símbolo vinho), nunca símbolo complementar sobre outra complementar.
- Avatar de redes sociais: sempre o símbolo em `uni-vinho-escuro`.
- Na papelaria, logotipo na frente e símbolo no verso.

## Composições

- **Distanciada (preferencial):** logotipo à esquerda, símbolo afastado à direita, mantendo a proporção.
- **Horizontal:** símbolo à direita do logotipo, espaço = 1/2 u; só alinhamento pela direita.
- **Vertical:** símbolo centralizado acima do logotipo, espaço = 1/2 u; só alinhamento centralizado.

## Área de proteção

O módulo é a altura da letra "U" do logotipo, livre em todo o perímetro — de textos, imagens, grafismos e limites do documento.

## Tagline

- "O nosso sorriso é único." em Georama Itálico (institucional) ou Georama Bold Itálico (destaque/Singular), caixa alta e baixa, entreletra 40 (estilos `tagline` e `tagline-destaque`).
- Vertical: abaixo do logotipo, à distância "h", alinhada à esquerda e com a largura do logotipo. Horizontal: ao lado do símbolo, com a largura do logotipo.
- Como título, a cor da tagline pode variar dentro da paleta do layout; a ênfase em bold itálico cai numa palavra ("O nosso sorriso é **único.**" ou "O nosso **sorriso** é único.").

## Assinatura com outras marcas

- Horizontal: distância de 1,5x a largura do símbolo (com símbolo) ou 2 U (só logotipo), alinhamento centralizado.
- Vertical: distância de 1x a altura do símbolo (com símbolo) ou 2 U (só logotipo).
- Defina a hierarquia pelo tamanho relativo das marcas.

## Submarca Singulares

- `uni-roxo` é a cor oficial das Singulares: símbolo e nome da Singular em roxo; logotipo em vinho (ou branco sobre vinho).
- Nome da Singular em Georama Itálico, caixa alta e baixa, entreletra 25, com a altura do "U".
- Prefira as versões distantes: evite juntar símbolo ao logotipo para não criar excesso de elementos.
- Espaços: 1/2 u ao lado, 3/4 u abaixo.
- Use o template de `assets/Singulares` (nome como texto editável) pelo componente `AssinaturaSingular`; nunca recomponha à mão.

## Submarcas Soluções

- **U fast:** símbolo + "Fast" em `uni-vinho-escuro` e `uni-goiaba`.
- **Sig U:** "Sig" + símbolo em `uni-vinho-escuro` e `uni-ciano`.
- Positiva: marca vinho sobre a cor da submarca; negativa: marca na cor sobre vinho.
- Todas as assinaturas (Banco U, Dental U, Mobile, RXScan, Sig U, UCX, U Fast, U Hub, U Rede) estão em `assets/Submarcas`, positivo e negativo; vitrine no componente `Submarcas`.

## Usos incorretos

Não altere para cor fora da paleta; não sobreponha com pouco contraste; não use fundo de pouco contraste; não distorça; não rotacione; não invada a área de arejamento; não mude a posição do símbolo; não inclua efeitos; não insira em formas que desconfigurem a marca. Na monocromática, não aplique preto sobre fundo colorido.
