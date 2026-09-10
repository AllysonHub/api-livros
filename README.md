# Criando API de livros 📔

API desenvolvida em Python utilizando FastAPI, com integração ao banco de dados MySQL para cadastro e consulta de livros.

## usando algumas tecnologias e suas funçoes:

[svg](https://github.com/AllysonHub/api-livros#usando-algumas-tecnologias-e-suas-fun%C3%A7oes)

🟣 **fastapi:** cria as rotas e disponibiliza a documentação automática;

🟣 **uvicorn:** inicia o servidor ASGI da aplicação;

🟣 **sqlalchemy:** representa tabelas e executa operações no banco;

🟣 **pymysql:** permite que o SQLAlchemy converse com o MySQL;

🟣 **pydantic-settings:** carrega configurações e variáveis de ambiente;

🟣 **python-dotenv:** auxilia na leitura de variáveis armazenadas em arquivos `.env`;

🟣 **mysql:** banco de dados utilizado para armazenar os livros.

---

## Banco de Dados 🗄️

Conexao com Banco de Dados feita e Funcionando!

A aplicação possui uma conexão configurada com o MySQL através do SQLAlchemy e PyMySQL.

🟣 configuração das informações do banco através de variáveis de ambiente;

🟣 criação do mecanismo de conexão com o banco;

🟣 criação da sessão do banco para realizar operações;

🟣 criação do modelo responsável por representar os livros no banco.

---

## Rotas 📡

A API possui atualmente as seguintes rotas:

🟣 **POST:** responsável por cadastrar novos livros;

🟣 **GET:** responsável por listar os livros cadastrados;

🟣 **GET por ID:** responsável por consultar um livro específico através do seu ID.

---

## Testes 🧪

Foram realizados testes durante o desenvolvimento para verificar o funcionamento da aplicação.

🟣 validação da inicialização da API;

🟣 validação da conexão com o banco de dados;

🟣 validação da rota `POST` de cadastro;

🟣 validação da rota `GET` de consulta;

🟣 validação da consulta de livro por ID.

---

## Documentação 📖

A API utiliza a documentação automática disponibilizada pelo FastAPI.

🟣 **Swagger UI:**

`http://127.0.0.1:8000/docs`

🟣 **ReDoc:**

`http://127.0.0.1:8000/redoc`

A documentação permite visualizar as rotas disponíveis e realizar testes diretamente pelo navegador.

---

## Desenvolvimento 🚀

O projeto foi desenvolvido em etapas, começando pela criação do repositório e preparação do ambiente, passando pela configuração da API e do banco de dados, até chegar às rotas de cadastro e consulta de livros.

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

🟣 validação das rotas `POST` e `GET`;

🟣 atualização da documentação do banco após as rotas de cadastro e consulta.

---

## Commits 📌

### 📅 Início do projeto

#### [chore: inicia repositorio da api de livros](https://github.com/AllysonHub/api-livros/commit/0eb5e539d95ae7330d836b39bda8586bd7da8802)

#### [chore: prepara pasta do projeto](https://github.com/AllysonHub/api-livros/commit/95f9d3731da0a80af3f7d0a193989bb85e5f756b)

#### [chore: adiciona dependencias da api](https://github.com/AllysonHub/api-livros/commit/aec364a95cddd73cbf256fd4669b7af5709f23df)

#### [chore: cria estrutura inicial da aplicacao](https://github.com/AllysonHub/api-livros/commit/08a4296086d41dfe8555db4e10c4fe4197521013)

#### [chore: protege configuracoes locais](https://github.com/AllysonHub/api-livros/commit/fd64486da76f2af25f629a88db82871e095c39e0)

---

### 📅 Configuração da API e Banco de Dados

#### [feat: configura conexao com mysql](https://github.com/AllysonHub/api-livros/commit/d70530323f1e179a32f1c8c394d4b7e140a14f1e)

#### [feat: cria aplicacao fastapi e rota de saude](https://github.com/AllysonHub/api-livros/commit/81782c9a29909dbcc3635101960de2171202220a)

#### [test: valida inicializacao da api](https://github.com/AllysonHub/api-livros/commit/42eaa48fc9872ca3a79ae714939f1ac696c11e03)

#### [test: valida inicializacao da api](https://github.com/AllysonHub/api-livros/commit/1db6d2f15b2078550c90db54a2f8147c845e5eb3)

#### [test: valida conexao com banco de dados](https://github.com/AllysonHub/api-livros/commit/8ca27a27630859b509bd0086cfb0e279b390936d)

#### [feat readme](https://github.com/AllysonHub/api-livros/commit/cd4d9c81bd24159d43d0b856c922d56dc4b644cc)

---

### 📅 Desenvolvimento das funcionalidades

#### [chore: prepara ambiente para a parte 2](https://github.com/AllysonHub/api-livros/commit/7c4f0eac5eb23fcca894e598cced32a5b463875a)

#### [feat: cria modelo de livros](https://github.com/AllysonHub/api-livros/commit/fe1dc38656fea79d455a75c0be49f98e94c46497)

#### [feat: adiciona schemas de livros](https://github.com/AllysonHub/api-livros/commit/6e51a2ef8cb0e8eea935971ae13c01d87fbb8c96)

#### [feat: cria sessao do banco](https://github.com/AllysonHub/api-livros/commit/afb3d7682a63f9169c3d3b4e6ac14c4bd06b8b21)

#### [feat: cria rota para cadastrar livros](https://github.com/AllysonHub/api-livros/commit/e46b4eeb13bf67d925c6327cef0e695fea68ae65)

#### [feat: cria rota para listar livros](https://github.com/AllysonHub/api-livros/commit/43787e152954e4fb85d750e0f95366981b38a85f)

#### [feat: cria consulta de livro por id](https://github.com/AllysonHub/api-livros/commit/33dd541f278979f4d9f05c8f49c5ea47d6ba4f38)

#### [atualizando req.txt](https://github.com/AllysonHub/api-livros/commit/b4ff6075b8b309ba20e54080b21ea777649b10dc)

#### [Fix(Banco de dados)](https://github.com/AllysonHub/api-livros/commit/e5d492809bcac223ca60c3abef55b87b44a696de)

#### [test: valida rotas post e get](https://github.com/AllysonHub/api-livros/commit/a5e6741d5687eea50701c574c8c38e086eaa7e01)

#### [docs: atualiza banco apos rotas de cadastro e consulta](https://github.com/AllysonHub/api-livros/commit/42ed0db0547499d35300eb07164993d359159e50)

---

## Status do projeto 📊

🟢 API criada;

🟢 FastAPI configurado;

🟢 MySQL conectado;

🟢 Banco de dados funcionando;

🟢 Modelo de livros criado;

🟢 Schemas criados;

🟢 Sessão do banco criada;

🟢 Cadastro de livros funcionando;

🟢 Listagem de livros funcionando;

🟢 Consulta por ID funcionando;

🟢 Rotas `POST` e `GET` testadas;

🟢 Documentação atualizada;

🟡 Projeto em desenvolvimento.
