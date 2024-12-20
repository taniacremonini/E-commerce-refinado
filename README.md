E-commerce - Sistema de Vendas Online
Descrição
Este é um projeto acadêmico de e-commerce desenvolvido como parte do bootcamp da Dio.me, no qual o objetivo é modelar e implementar um banco de dados para gerenciar as operações de uma plataforma de vendas online. O sistema contempla funcionalidades como o cadastro de clientes, gerenciamento de produtos, registro e controle de pedidos, gestão de estoque, processamento de pagamentos e rastreamento de entregas.

A modelagem do banco de dados foi realizada utilizando o MySQL Workbench, e o modelo de dados foi criado utilizando o Diagrama Entidade-Relacionamento (EER).

Funcionalidades
Cadastro de clientes: Clientes podem ser cadastrados como pessoa física ou jurídica.
Gerenciamento de produtos: Produtos fornecidos por diferentes fornecedores e terceiros vendedores.
Registro e controle de pedidos: Um cliente pode realizar múltiplos pedidos, e um pedido pode conter vários produtos.
Gestão de estoque: Controle da quantidade de produtos disponíveis no estoque.
Processamento de pagamentos: Suporte para métodos de pagamento como cartão de crédito, boleto e PIX.
Rastreamento de entregas: Cada entrega possui status e código de rastreio.
Tecnologias Utilizadas
Banco de Dados: MySQL
Ferramenta de Modelagem: MySQL Workbench
Linguagem de Consulta: SQL
Modelo de Dados: Diagrama Entidade-Relacionamento (EER)
Diagrama EER
A modelagem do banco de dados foi realizada por meio de um Diagrama Entidade-Relacionamento (EER) utilizando o MySQL Workbench. Abaixo, você pode ver a estrutura geral do banco de dados:

https://github.com/taniacremonini/E-commerce-refinado/blob/main/Projeto-E_commerce.png

Tabelas do Banco de Dados
As principais tabelas do banco de dados incluem:

Cliente: Contém informações sobre os clientes.
Pedido: Armazena os pedidos realizados pelos clientes.
Produto: Gerencia os produtos disponíveis para venda.
Estoque: Controla a quantidade de cada produto disponível.
Fornecedor: Contém informações sobre os fornecedores de produtos.
Pagamento: Registra os pagamentos realizados pelos clientes.
Entrega: Armazena os dados de rastreamento de entregas.
Como Rodar o Projeto
Clone este repositório:

bash
Copiar código
git clone https://github.com/seu_usuario/ecommerce.git
Abra o MySQL Workbench e importe o arquivo .sql contendo a estrutura do banco de dados.

Após importar o banco de dados, você pode começar a interagir com ele por meio do MySQL Workbench ou de uma aplicação que utilize o banco.

Como Contribuir
Faça um fork deste repositório.
Crie uma branch para a sua feature (git checkout -b minha-feature).
Comite suas alterações (git commit -am 'Adiciona nova funcionalidade').
Envie para o repositório remoto (git push origin minha-feature).
Abra um pull request.
Licença
Este projeto está licenciado sob a MIT License - consulte o arquivo LICENSE para mais detalhes.
