Conceito inicial de um banco de dados de uma oficina, construído utilizando MYSQL.

- Tabela CLIENTES armazena os dados dos clientes;
- Tabela VEICULO_CLIENTE armazena as informações dos veiculos de cada cliente, podendo ter mais de um, como é o casos das locadoras e transportadoras;
- Tabela SETORES lista todos os setores da oficina;
- Tabela CARGOS lista todos os cargos da oficina;
- Tabela FUNCIONARIOS armazena os dados dos funcionários;
- Tabela MAO_OBRA lista os serviços e seu valor sem incluir os produtos utilizados;
- Tabela PRODUTOS lista os produtos utilizados nos serviços, sua marca e seu valor final;
- Tabela ESTOQUE lista a quantidade de produtos armazenados;
- Tabela SERVICO_REALIZADO recebe todas as informações referente ao serviço prestado,incluindo campo para serviços adicionais;
- Tabela FORNECEDORES lista todos os fornecedores homologados e seu representante;
- Tabela PEDIDO_COMPRAS recebe os produtos que precisam ser adquiridos junto aos fornecedores;
- Criado VIEW RELACAO_CLIENTE_VEICULO para exibir relação entre cliente e seus veiculos;
- Criado VIEW GASTO_POR_CLIENTE para exibir valor total gasto por cada cliente;
- Criado VIEW SERVIÇOS_REALIZADOS para exibir todas as informações sobre o serviço prestado que pode ser apresentado para o cliente;
- Criado VIEW PEDIDO_DE_COMPRAS para exibir um pedido de compras basicamente estruturado;
- Criado VIEW NIVEL_ESTOQUE para exibir estoque detalhado;
- Os filtros SELECT criados com ajuda das VIEWS para facilitar construção e visualização do código.
  ![oficina_ERR](https://github.com/Rafael-soares-oliveira/SQL/assets/136133825/baa9389d-186d-4c44-92cb-2b0442255a21)
