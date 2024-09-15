  <h1 align="center">
    <img alt="Logo" src="https://res.cloudinary.com/dvargas42/image/upload/v1726376479/icon_ff0qhi.png" width="200px">
  </h1>

  <h3 align="center">
  This Web Server is part of the In.orbit project
  </h3>

  <p align="center">The best way to control your goals</p>

  <p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/dvargas42/in-orbit-srv?color=%238958B5">

  <a href="https://www.linkedin.com/in/daniel-santos-040983ab/" target="_blank" rel="noopener noreferrer">
    <img alt="Made by" src="https://img.shields.io/badge/made%20by-daniel%20vargas-%238958B5">
  </a>

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/dvargas42/in-orbit-srv?color=%238958B5">

  <a href="https://github.com/dvargas42/in-orbit-srv/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/dvargas42/in-orbit-srv?color=%238958B5">
  </a>

  <a href="https://github.com/dvargas42/in-orbit-srv/issues">
    <img alt="Repository issues" src="https://img.shields.io/github/issues/dvargas42/in-orbit-srv?color=%238958B5">
  </a>

  <img alt="GitHub" src="https://img.shields.io/github/license/dvargas42/dvargas42?color=%238958B5">
  </p>

  <p align="center">
    <a href="#%EF%B8%8F-about-the-project">About the project</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href="#-technologies">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href="#-getting-started">Getting started</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href="#-how-to-contribute">How to contribute</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href="#-license">License</a>
  </p>

  ## 💇🏼 About the project

  This service is responsible for providing data to the In-Orbit-srv APP. It provides the goal creation routes, goal completion, pending goals and goals summary.

  <br>

  ## 🚀 Technologies

  Technologies that I used to develop this api

  - [NodeJs 20](https://nodejs.org/pt)
  - [Fastify 9](https://fastify.dev/)
  - [TypeScript 18](https://www.typescriptlang.org/)
  - [Dayjs 1.11](https://day.js.org/en/)
  - [Drizzle-orm 0.33](https://orm.drizzle.team/)
  - [Postgres 0.441](https://www.postgresql.org/)
  - [Zod 3.23](https://zod.dev/)
  - [Docker 27.3](https://www.docker.com/)
  - [BiomeJS 1.9](https://biomejs.dev/pt-br/)

  ## 💻 Getting started

  ### Requirements

  - [Node.js](https://nodejs.org/en/)
  - [Yarn](https://classic.yarnpkg.com/) or [npm](https://www.npmjs.com/)


  **Clone the project and access the folder**

  ```bash
  $ git clone https://github.com/dvargas42/in-orbit-srv.git
  ```

  **Follow the steps below**

  ```bash
  # Install the dependencies
  $ npm i

  # Up docker container
  $ docker compose up -d

  # Run migrations
  $ npx drizzle-kit migrate 

  # Run script to load seeds
  $ npm run seed

  # To run locally
  $ npm run dev

  # If you want a client to see the database tables
  $ npx drizzle-kit studio

  # Well done, project is started!
  ```

  ## 🤔 How to contribute

  **Make a fork of this repository**

  ```bash
  # Fork using GitHub official command line
  # If you don't have the GitHub CLI, use the web site to do that.

  $ gh repo fork dvargas42/in-orbit-srv
  ```

  **Follow the steps below**

  ```bash
  # Clone your fork
  $ git clone your-fork-url && cd in-orbit-srv

  # Create a branch with your feature
  $ git checkout -b my-feature

  # Make the commit with your changes
  $ git commit -m 'feat: My new feature'

  # Send the code to your remote branch
  $ git push origin my-feature
  ```

  After your pull request is merged, you can delete your branch

  ## 📝 License

  This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

  ---

  Made with 💜 &nbsp;by Daniel Vargas 👋 &nbsp;[See my linkedin](https://www.linkedin.com/in/daniel-santos-040983ab/)
