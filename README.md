# Projeto Django (Bolsa de valores)

## Estrutura investimento
- data: dd/mm/aaaa
- código: 4 letras e 1 ou 2 números 
- quantidade: int
- valor unitário: double
- compra/venda 
- Corretagem: double
- valor da operação: valor unitário x quantidade
- taxa b3: 0.03% * valor operação
- valor total:
	Se for compra:
		valor total = valor operação + corretagem + taxa b3
	Se for venda:
		valor total = valor operação - corretagem - taxa b3

## Investidor
- usuário
- senha

## Ativo
- código
- nome
- cnpj


## Funcionalidades
- Login
- Cadastrar usuário
- CRUD investimentos
- Ordenar e filtrar os investimentos


e-mail: brunoleal@ifpi.edu.br