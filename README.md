<h1 align="center">🔗 API Back-End</h1>

<p align="center">🚀 API Back-End - Envio de e-mail com enquete para usuários 🚀</p>

<p align="center">
 <a href="#projeto">Projeto</a> |
 <a href="#tecnologias">Tecnologias</a> | 
 <a href="#roadmap">Pré-Requisitos</a> | 
 <a href="#contribuicao">Contribuição</a> | 
 <a href="#licenc-a">Licença</a>
</p>

<h2 align="left">💻 Projeto</h2>
<p>Este é um projeto desenvolvido com foco em Node.js durante a Next Level Week, realizada pela [@Rocketseat](https://github.com/Rocketseat) durante os dias 22 a 26 de Fevereiro de 2021.</p>

<h2 align="left">🛠 Tecnologias</h2>
<p>As seguintes ferramentas foram usadas na construção do projeto:</p>

- [TypeScript](https://nodejs.org/en/)
- [Node.js](https://nodejs.org/en/)
- [TypeORM](https://typeorm.io/#/)
- [SQLite](https://www.sqlite.org/index.html)
- [Express](https://expressjs.com/pt-br/)
- [Yup](https://www.npmjs.com/package/yup?activeTab=readme#api)
- [Handlebars](https://handlebarsjs.com/)
- [Jest](https://jestjs.io/)
- [Nodemailer](https://nodemailer.com/about/)
- [Ethereal](https://ethereal.email/)


<h2 align="left">✅ Features</h2>

- [x] Cadastro de novos usuários utilizando nome e e-mail.
- [x] Validação de cadastro de usuários, impedindo que um usuário se cadastre com e-mail já previamente cadastrado
- [x] Cadastro de enquete utilizando
- [x] Criação e Envio de E-mail com Enquete e Usuário
- [x] Cálculo de NPS
 
<h2 align="left">✅ Pré Requisitos </h2>

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/), [Insomnia](https://insomnia.rest/download/), [BeeKeeper](https://www.beekeeperstudio.io/). 
Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)

### 🎲 Rodando a Aplicação

```bash
# Clone este repositório
$ git clone <https://github.com/luizfelipeb/nlw4-nodejs.git>

# Acesse a pasta do projeto no terminal/cmd
$ cd nlw4-nodejs

# Instale as dependências
$ npm install

# Execute a aplicação em modo de desenvolvimento
$ npm run dev

# O servidor inciará na porta:3333 - acesse <http://localhost:3333>

# Banco já com registros para envio e visualização dos e-mails

# Arquivo Insomnia.json para teste da API na raíz do projeto. Importar para o Insomnia

# Utilizar Insomnia para teste de métodos GET e POST. 

# Utilizar Beekeeper para visualização de dados para serem preenchidos no corpo da requisição dos métodos POST no Insomnia.
# Abrir o arquivo em ./database/database.sqlite

# Visualização do e-mail com Ethereal via link gerado no console após execução do Método POST em SendEmail no Insomnia.

```

### 📃Licença
Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](https://github.com/luizfelipeb/nlw4-nodejs/blob/main/LICENSE.md) para mais detalhes.

