Criando API de livros 📔

API desenvolvida em Python utilizando FastAPI, com integração ao banco de dados MySQL para cadastro, consulta, atualização e exclusão de livros.

Usando algumas tecnologias e suas funções:

svg

🟣 fastapi: cria as rotas e disponibiliza a documentação automática;

🟣 uvicorn: inicia o servidor ASGI da aplicação;

🟣 sqlalchemy: representa tabelas e executa operações no banco;

🟣 pymysql: permite que o SQLAlchemy converse com o MySQL;

🟣 pydantic-settings: carrega configurações e variáveis de ambiente;

🟣 python-dotenv: auxilia na leitura de variáveis armazenadas em arquivos .env;

🟣 mysql: banco de dados utilizado para armazenar os livros.

Banco de Dados 🗄️

Conexão com Banco de Dados feita e funcionando!

A aplicação possui uma conexão configurada com o MySQL através do SQLAlchemy e PyMySQL.

🟣 configuração das informações do banco através de variáveis de ambiente;

🟣 criação do mecanismo de conexão com o banco;

🟣 criação da sessão do banco para realizar operações;

🟣 criação do modelo responsável por representar os livros no banco;

🟣 padronização do modelo de livros;

🟣 preparação da estrutura para operações completas de CRUD.

Rotas 📡

A API possui atualmente as seguintes rotas:

🟣 POST: responsável por cadastrar novos livros;

🟣 GET: responsável por listar os livros cadastrados;

🟣 GET por ID: responsável por consultar um livro específico através do seu ID;

🟣 PUT: responsável por atualizar as informações de um livro existente;

🟣 DELETE: responsável por excluir um livro através do seu ID.

A API possui atualmente as operações completas de CRUD:

🟢 Create: cadastro de livros;

🟢 Read: listagem e consulta de livros;

🟢 Update: atualização de livros;

🟢 Delete: exclusão de livros.

Testes 🧪

Foram realizados testes durante o desenvolvimento para verificar o funcionamento completo da aplicação.

🟣 validação da inicialização da API;

🟣 validação da conexão com o banco de dados;

🟣 validação da rota POST de cadastro;

🟣 validação da rota GET de consulta;

🟣 validação da consulta de livro por ID;

🟣 validação da rota PUT de atualização;

🟣 validação da rota DELETE de exclusão;

🟣 confirmação das rotas completas do CRUD;

🟣 validação do CRUD completo através do Swagger.

Documentação 📖

A API utiliza a documentação automática disponibilizada pelo FastAPI.

🟣 Swagger UI:

http://127.0.0.1:8000/docs

🟣 ReDoc:

http://127.0.0.1:8000/redoc

A documentação permite visualizar as rotas disponíveis, consultar o contrato da API e realizar testes diretamente pelo navegador.

O contrato da API foi validado para preparar a integração com o frontend.

Desenvolvimento 🚀

O projeto foi desenvolvido em etapas, começando pela criação do repositório e preparação do ambiente, passando pela configuração da API e do banco de dados, criação das operações de cadastro e consulta, até a implementação do CRUD completo de livros.

🟣 preparação do repositório;

🟣 instalação das dependências da API;

🟣 criação da estrutura inicial da aplicação;

🟣 proteção das configurações locais;

🟣 configuração da conexão com MySQL;

🟣 criação da aplicação FastAPI e rota de saúde;

🟣 validação da inicialização da API;

🟣 validação da conexão com o banco;

🟣 preparação do ambiente para a parte 2;

🟣 criação do modelo de livros;

🟣 criação dos schemas de livros;

🟣 criação da sessão do banco;

🟣 criação da rota para cadastrar livros;

🟣 criação da rota para listar livros;

🟣 criação da consulta de livro por ID;

🟣 atualização das dependências;

🟣 correções no banco de dados;

🟣 validação das rotas POST e GET;

🟣 atualização da documentação do banco após as rotas de cadastro e consulta;

🟣 preparação do ambiente para a parte 3;

🟣 padronização do modelo de livros;

🟣 padronização dos schemas de livros;

🟣 preparação do arquivo principal para as operações de CRUD;

🟣 criação da rota para atualizar livros;

🟣 criação da rota para excluir livros;

🟣 confirmação das rotas completas do CRUD;

🟣 validação do CRUD completo através do Swagger;

🟣 confirmação do contrato da API para integração com o frontend.

Commits 📌

📅 Início do projeto

chore: inicia repositorio da api de livros
chore: prepara pasta do projeto
chore: adiciona dependencias da api
chore: cria estrutura inicial da aplicacao
chore: protege configuracoes locais


📅 Configuração da API e Banco de Dados

feat: configura conexao com mysql
feat: cria aplicacao fastapi e rota de saude
test: valida inicializacao da api
test: valida inicializacao da api
test: valida conexao com banco de dados
feat readme


📅 Desenvolvimento das funcionalidades

chore: prepara ambiente para a parte 2
feat: cria modelo de livros
feat: adiciona schemas de livros
feat: cria sessao do banco
feat: cria rota para cadastrar livros
feat: cria rota para listar livros
feat: cria consulta de livro por id
atualizando req.txt
Fix(Banco de dados)
test: valida rotas post e get
docs: atualiza banco apos rotas de cadastro e consulta


📅 Desenvolvimento do CRUD

chore: prepara ambiente para a parte 3
fix: padroniza modelo livro
fix: padroniza schemas de livros
fix: prepara arquivo principal para crud
feat: cria rota para atualizar livros
feat: cria rota para excluir livros
test: confirma rotas completas do crud
test: valida crud completo pelo swagger
docs: confirma contrato da api para frontend

Status do projeto 📊

🟢 API criada;

🟢 FastAPI configurado;

🟢 MySQL conectado;

🟢 Banco de dados funcionando;

🟢 Modelo de livros criado e padronizado;

🟢 Schemas criados e padronizados;

🟢 Sessão do banco criada;

🟢 Cadastro de livros funcionando;

🟢 Listagem de livros funcionando;

🟢 Consulta por ID funcionando;

🟢 Atualização de livros funcionando;

🟢 Exclusão de livros funcionando;

🟢 CRUD completo implementado;

🟢 Rotas POST, GET, PUT e DELETE testadas;

🟢 CRUD completo validado pelo Swagger;

🟢 Contrato da API confirmado para o frontend;

🟢 Documentação atualizada;

🟡 Projeto em desenvolvimento.