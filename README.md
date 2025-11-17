# Projeto Blog Pessoal - Frontend com React

<br />

<div align="center">     
     <img src="https://i.imgur.com/AzshGmS.png" title="source: imgur.com" width="50%"/>
</div> 
<br /> 

<div align="center">   
    <img src="https://img.shields.io/github/languages/top/rafaelq80/blogpessoal_react_t83?style=flat-square" />
    <img src="https://img.shields.io/github/repo-size/rafaelq80/blogpessoal_react_t83?style=flat-square" />   
     <img src="https://img.shields.io/github/languages/count/rafaelq80/blogpessoal_react_t83?style=flat-square" />
    <img src="https://img.shields.io/github/last-commit/rafaelq80/blogpessoal_react_t83?style=flat-square" />
    <img src="https://img.shields.io/github/issues/rafaelq80/blogpessoal_react_t83?style=flat-square" />
  <img src="https://img.shields.io/github/issues-pr/rafaelq80/blogpessoal_react_t83?style=flat-square" />
    <img src="https://img.shields.io/badge/status-em%20desenvolvimento-yellow?style=flat-square" /> 
</div>

<br />

## 1. Descrição

O **Blog Pessoal - Frontend** é uma aplicação web desenvolvida com **React** e **TypeScript**, com o objetivo de consumir e exibir dados de uma API REST construída com **Spring Boot**. A aplicação permite a visualização, criação, edição e exclusão de postagens de blog, categorizadas por temas e vinculadas a usuários autenticados.

Funcionalidades:

1. Cadastro e login de usuários
2. Listagem e gerenciamento de postagens
3. Criação, edição e exclusão de temas
4. Associação entre postagens, temas e autores
5. Navegação entre páginas com React Router Dom
6. Consumo de API com Axios
7. Estilização com Tailwind CSS

<br />

## 2. Autenticação e Validação de Token JWT

### Fluxo de Autenticação

1. O usuário realiza o login com **e-mail** e **senha**.
2. A aplicação faz uma requisição para a API, que retorna um token **JWT**.
3. O token é armazenado na **Context API** para uso em futuras requisições autenticadas.
4. Nas rotas protegidas, o token é validado antes do acesso aos recursos.

### Controle de Autenticação

- Se o token expirar ou for inválido, o usuário será redirecionado para a página de login.

<br />

## 3. Tecnologias Utilizadas

| Tecnologia           | Finalidade                            |
| -------------------- | ------------------------------------- |
| **React**            | Biblioteca JavaScript para interfaces |
| **TypeScript**       | Superset do JavaScript com tipagem    |
| **Tailwind CSS**     | Estilização com classes utilitárias   |
| **Axios**            | Consumo de APIs REST                  |
| **React Router DOM** | Roteamento SPA                        |
| **Vite**             | Build tool rápido para projetos React |

<br />

## 4. Pré-requisitos

Antes de iniciar o projeto, certifique-se de ter instalado:

- [Node.js](https://nodejs.org/) (versão 16 ou superior)
- [Yarn](https://yarnpkg.com/)
- [Git](https://git-scm.com/)
- [Visual Studio Code](https://code.visualstudio.com/) ou outro editor
- Backend - Spring ([Repositório da API](https://github.com/rafaelq80/blogpessoal_spring_t83))

<br />

## 5. Como executar o projeto localmente

1. **Clone o repositório:**

```bash
git clone https://github.com/rafaelq80/blogpessoal_react_t83.git
```

2. **Acesse a pasta do projeto:**

```bash
cd blogpessoal_react_t83
```

3. **Instale as dependências:**

```bash
yarn
```

4. **Execute o projeto em modo desenvolvimento:**

```bash
yarn dev
```

5. **Acesse a aplicação em:**

```
http://localhost:5173
```

<br />


## 6. Integração com a API Backend

A aplicação se comunica com a API do projeto:

🔗 [Blog Pessoal - Backend Spring Boot](https://github.com/rafaelq80/blogpessoal_spring_t83)

> A URL base da API deve ser configurada (ex: `http://localhost:8080`) em um arquivo de configuração, como `.env`, ou diretamente nos serviços do Axios.

<br />


## 7. Estrutura de Diretórios

```
src/
│
├── assets/           → Imagens e ícones
├── components/       → Componentes reutilizáveis
├── contexts/         → Gerenciamento de estado global (ex: autenticação)
├── models/           → Interfaces e tipos do projeto
├── pages/            → Páginas da aplicação
├── services/         → Configuração do Axios
├── utils/            → Funções auxiliares (alerts)
├── App.css           → Estilos do Componente raiz
├── App.tsx           → Componente raiz
├── main.tsx          → Entrada da aplicação
└── index.css         → Estilos globais com Tailwind
```

<br />


## 8. Implementações futuras

- Upload de imagem de perfil para o usuário
- Responsividade aprimorada
- Validações com React Hook Form
- Testes com Jest + React Testing Library

<br />


## 9. Contribuição

Contribuições são bem-vindas!

Se você encontrou algum problema ou deseja propor melhorias:

- Abra uma **issue**
- Envie um **pull request**
- Compartilhe com colegas aprendizes!

<br />


## 10. Contato

Desenvolvido por [**Rafael**](https://github.com/rafaelq80)
Dúvidas ou sugestões? Entre em contato pelo GitHub ou abra uma issue no repositório.

