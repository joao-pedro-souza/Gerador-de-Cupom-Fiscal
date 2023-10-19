# Gerador de Cupom Fiscal

Código Python que cria uma classe CupomFiscal.

Recebe 3 parâmetros:

**nome_loja=str**: Adiciona o nome da loja no topo do Cupom Fiscal <br>
**cliente=str**: Adiciona o nome do cliente ao cartão fiscal <br>
**produtos=list**: Uma lista de listas com os produtos, deve ter 4 índices: <br>

[0] = nome do produto, <br>
[1] = preço do produto, <br>
[2] = unidades vendidas, <br>
[3] = preço total <br>

Exemplo de declaração:  <br>

`cupom = CupomFiscal('Loja', 'Cliente', [['Produto 1', 1, 1, 1], ['Produto 2', 1, 1, 1]])` <br><br>

## Cupom gerado:

![image](https://github.com/joao-pedro-souza/Gerador-de-Cupom-Fiscal/assets/56794682/ef10b7bb-b611-4bf4-9b6d-8319ecb3bfe6)
