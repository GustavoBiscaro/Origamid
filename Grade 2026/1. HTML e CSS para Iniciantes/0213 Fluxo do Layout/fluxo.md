# Fluxo do Layout
O fluxo do layout no HTML ocorre conforme o modo de escrita definido. Por padrão, de cima para baixo, da esquerda para a direita.

*SPAN*
Tag genérica que não poussuí nenhum estilo pré-definido/semântica. É equivalente a uma div, mas sem o display block.

# Display Inline e Block
Define como a caixa (box model) irá se comportar.

## inline
Respeita o fluxo da escrita sem iniciar uma nova linha, não é possível definir valores de width, height, margin (top/bottom) e etc. É o estilo padrão.

## block
Inicia uma nova linha e não permite que outros elementos sejam posicionados em sua linha. Aceita todas as propriedades do box model. Estilo inicial de elementos como h1, p, div e outros.

# None e Inline-block
## none
Remove o elemento completamente da tela.

## inline-block
O elemento continua inline, mas passa a receber as propriedades do box model.

# Posicionamento
Para posicionamentos complexos, como o da imagem [nimbus.png] abaixo, utilizamos as propriedades display grid (CSS Grid Layout) e flex (Flexbox)