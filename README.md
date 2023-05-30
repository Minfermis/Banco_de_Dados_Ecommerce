# Projeto Conceitual de Banco de Dados – E-COMMERCE </br></br>


### Descrição do Desafio
O esquema deverá ser adicionado a um repositório do Github para futura avaliação do desafio de projeto. Adicione ao Readme a descrição do projeto conceitual para fornecer o contexto sobre seu esquema.
## Objetivo:
Refine o modelo apresentado acrescentando os seguintes pontos:</br>
Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações;</br>
Pagamento – Pode ter cadastrado mais de uma forma de pagamento;</br>
Entrega – Possui status e código de rastreio;

## Descrição do Meu Projeto:

Antes de tudo, quis deixar de uma forma clara, e com o fluxograma que estou familiarizado fazer compras na Internet. Confesso que demorei horas quebrando a cabeça. Fiz até um esqueleto pelo “draw.io” para achar uma maneira de deixar claro o modelo.</br></br>No inicio foi separado três tipos de "Entidades":
Pessoa Física, Pssoa jurídica e Revendedor. Esses três tem os atributos padrões para prenchimento dos dados. </br>
</br>Em seguida temos a segunda parte com duas Entidades: Local de Entrega e Pedido. O Local de Entrega leva para Entidade de Rastreio. Onde ali esperamos o status da confirmação do pagamento para o pedido ser enviado. E depois temos o Pedido que leva ao Produto e do Produto passa para o a pesquisa de Disponibilidade em duas Entidades importantes. Estoque e Fornecedor. Dando a disponibilidade do produto para o Pedido, os dados vão para o carrinho de compra. Onde temos a próxima etapa que é a forma de pagamento. Lá temos 3 formas para pagar que é crédito, débito e pix. </br></br>
Aprovando o pagamento voltamos com a informação para Status de Rastreio que faz a saida com os produtos. 
