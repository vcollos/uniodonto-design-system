# AssinaturaSingular

Gerador da assinatura de cada Singular a partir do template oficial (`assets/Singulares`): símbolo e logotipo em curvas, nome da Singular como texto editável em Georama Itálico.

## O que o consumidor fornece

- O nome da Singular, em caixa alta e baixa ("Rio Grande do Norte", "Vale do Paraíba").
- A versão: horizontal distante A/B (preferencial), horizontal próxima A/B, vertical distante ou vertical próxima; positiva (fundo branco) ou negativa (fundo vinho).

## Como funciona

- O preview carrega o SVG do template, troca o `<text>` pelo nome digitado (um único `tspan`, entreletra .025em), recalcula o `viewBox` pela caixa real do desenho e permite baixar o resultado.
- Em código: faça o mesmo — `fetch` do arquivo, substitua o conteúdo do `<text>`, ajuste o `viewBox` com `getBBox()`. Carregue Georama itálico (`tokens.css`) antes de medir.
- Para gráfica ou fornecedor, converta o nome em curvas depois de gerar (o SVG não embute a fonte).

## Regras

- `uni-roxo` é a cor oficial das Singulares: símbolo e nome em roxo; logotipo em vinho (ou branco na negativa).
- Nome em Georama Itálico, caixa alta e baixa, entreletra 25, com a altura do "U".
- Prefira as versões distantes; evite juntar símbolo ao logotipo para não criar excesso de elementos.
- Espaços: 1/2 u ao lado, 3/4 u abaixo. Área de proteção = altura do "U".
- A Singular também assina com o selo SomosCoop (`AssinaturaSomosCoop`), em `uni-roxo` no timbrado.

## Não faça

- Não mude fonte, cor, inclinação ou posição do nome; não abrevie com siglas que não sejam o nome oficial da Singular.
