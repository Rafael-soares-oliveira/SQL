Conceito inicial de um banco de dados de um ecommerce de peças de bicicletas.

- Tabela CLIENTS armazena os dados cadastrais dos clientes;
- Tabela ORDERS armazena um pedido de compra do cliente sem especificar produtos, valores ou quantidade. O pedido, inicialmente, entra como 'EM PROCESSAMENTO' até ser definido como 'CONFIRMADO' ou 'CANCELADO' pelo cliente;
- Tabela PAYMENT armazena o tipo de pagamento, com possibilidade de acrescentar novos atributos, como desconto e particularidades bancárias;
- Tabela PRODUCT_ORDER armazena as informações do pedido, item, quantidade e situação perante o estoque, este último apresenta valor diferente apenas no caso de falha no controle de estoque;
- Tabela PRODUCTS irá listar todos os produtos disponíveis para venda, seu valor, categoria e marca;
- Tabela STORAGE_PRODUCT lista onde os produtos estão armazenados e a quantidade do estoque;
- Tabela PRODUCT_SUPPLIER lista os pedidos de abastecimento para fornecedores;
- Tabela SUPPLIER lista todos os fornecedores;
- Tabela SHIPPING armazena as informações da transportadora responsável pelo pedido;
- Tabela SHIPPING_COMPANY lista todas as empresas transportadoras homologadas;
- Tabela SHIPPING_AREA agrupa as cidades em áreas para facilitar o planejamento logístico.
  
![Diagrama_ecommerce](https://github.com/Rafael-soares-oliveira/SQL/assets/136133825/64833c66-389e-4812-a517-b8795ae7412d)
