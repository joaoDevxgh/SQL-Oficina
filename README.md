Sistema de Gerenciamento de Oficina — Banco de Dados
Este projeto representa o modelo de banco de dados para o gerenciamento de uma Oficina Mecânica, desenvolvido com base em um modelo entidade-relacionamento (ER) e convertido para o modelo lógico relacional.
📊 Modelo Conceitual
O modelo conceitual foi criado para representar os principais processos de uma oficina mecânica, incluindo:

Gestão de veículos

Controle de peças

Execução de serviços

Acompanhamento de ordens de serviço (OS)

Gestão de mecânicos e equipes

🏗️ Script SQL de Criação do Banco
O script para criação do banco de dados está no arquivo database.sql.

Banco: Oficina
Inclui as tabelas:

Veiculo

Mecanicos

Equipe

Tabela_OS

Equipe_has_Tabela_OS

Pecas

Servicos

Execucao_Servicos

🧠 Funcionamento Geral do Banco
O fluxo principal do sistema segue as etapas:

Cadastro dos veículos e clientes.

Cadastro dos mecânicos e formação de equipes.

Abertura de uma ordem de serviço (OS).

Vinculação de uma equipe à OS.

Seleção de peças e serviços associados ao veículo.

Execução dos serviços, atribuindo o mecânico responsável, data e status.

Fechamento da OS após conclusão.

🏗️ Tecnologias Utilizadas
💾 MySQL / MariaDB

🗺️ Workbench (modelagem visual)

🐘 SQL
