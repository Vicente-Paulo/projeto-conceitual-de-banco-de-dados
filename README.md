## Refinando um Projeto Conceitual de Banco de Dados – E-COMMERCE

### Derscrição do refinamento do esquema
Este esquema foi refinado com a inclusão da entidade "cadastro" contendo atributos como conta, o tipo de pessoa (se física ou juridica), forma de pagamento e cartões por bandeira do cliente, já o tipo de relacionamento é de um para muitos, pois um cliente pode ter vários cadastros. Também foi incluído a entidade "entrega" para gerar os atributos de status e código de rastreio, ainda foi gerado a entidade "Entrega do pedido" que foi o resultado do relacionamento de muitos para muitos entre as entidades "entrega" e "Pedido".
