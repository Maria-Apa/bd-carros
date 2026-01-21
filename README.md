# Carro Fácil — Banco de Dados Relacional (MySQL)
O Carro Fácil é o meu primeiro projeto, um banco de dados desenvolvido em MySQL Workbench para representar um sistema simples de gerenciamento de veículos, clientes, locações e pagamentos.

💻 O objetivo deste projeto foi praticar:

- Modelagem relacional.
- Construção de diagramas ER.
- Uso de chaves primárias e estrangeiras.
- Boas práticas de criação de tabelas.
- Organização de scripts SQL para repositórios GitHub.

⚙️ Tecnologias Utilizadas:

- MySQL 8+.
- MySQL Workbench (Forward Engineer).
- SQL (DDL).

🛠️ Estruturas Presentes no Banco:
1. Carros: Tabela que armazena os veículos disponíveis. <br>
Inclui atributos como modelo, marca, ano e placa.
2. Clientes:
Registra informações dos clientes cadastrados. <br>
Como, nome, cpf, e-mail e telefone.
3. Locações: 
Armazena os registros de retirada e devolução de veículos. <br>
Possui chave estrangeira para carros e clientes.
4. Pagamentos:
Controla valores e datas de pagamentos referentes às locações.
