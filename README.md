# Login Page

## Tecnologias Utilizadas

- Java e Spring Boot para a API
- Banco de dados H2
- JWT para autenticação
- Angular 17 para o frontend

## Descrição

Este é um projeto fullstack desenvolvido para fornecer funcionalidades de login e registro. O backend foi implementado em Java usando o framework Spring Boot, com um banco de dados H2 para armazenamento de dados e JWT para autenticação de usuários. O frontend foi construído com Angular 17.

## Instalação e Configuração

1. Clone este repositório.
2. Certifique-se de ter o Java e o Angular CLI instalados em sua máquina, caso não tenha o angular execute o seguinte script no terminal "npm i -g @angular/cli".
3. Execute o npm install para a instalação de dependecias no projeto de Front.

## Como Executar o Projeto

Para executar o projeto, siga estas etapas:

1. Navegue até o diretório do backend e execute a aplicação.
2. Navegue até o diretório do frontend e execute o comando `npm start`.
3. Abra um navegador da web e acesse `http://localhost:4200/login`.

## Funcionalidades Principais

- Login de usuários.
- Registro de novos usuários.
- Autenticação usando tokens JWT.
- Proteção de rotas que exigem autenticação.

## 📍 Rotas da Aplicação

Aqui você pode listar as principais rotas da sua API e quais são os corpos de requisição esperados.

| Rota               | Descrição                                          
|----------------------|-----------------------------------------------------
| <kbd>/signup</kbd>     | Página para se cadastrar
| <kbd>/login</kbd>     | Página para fazer login
| <kbd>/user</kbd>     | Página protegida que apenas usuários logados podem acessar
