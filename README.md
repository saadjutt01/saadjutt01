### Hey, I'm Saad!

### I'm the co-founder of [Tetrahex](https://tetrahex.com/) (orignially Full Stack coder + DevOps developer).

It's a small group of skilled full-stack developers developing and delivering web app since 2015.

Started our journey with Ruby on Rails and ReactJS. With the time, also worked on angularJS/angular2...12 and NodeJS.
Focused to deliever application with up-to-date best practices coding standards with Test Driven Development.

---

Working as CEO & Solution Architect for Tetrahex.

- 🔭 I’m currently working on [sasjs](https://github.com/sasjs) framework.
- 🌱 I’m constantly learning and practicing NodeJS best practices.
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about NodeJS/ExpressJS/CI-CD Automation/DevOps/AWS

### Languages and Tools:

<img align="left" alt="Visual Studio Code" width="36px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" style="padding-right:10px;" />
<img align="left" alt="Amazon Web Services" width="36px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original.svg" style="padding-right:10px;" />
<img align="left" alt="Node.js" width="36px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" style="padding-right:10px;" />
<img align="left" alt="React" width="36px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" style="padding-right:10px;" />
<img align="left" alt="Angular" width="36px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/angularjs/angularjs-original.svg" style="padding-right:10px;" />
<img align="left" alt="Gatsby" width="36px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/gatsby/gatsby-original.svg" style="padding-right:10px;" />
<img align="left" alt="JavaScript" width="36px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" style="padding-right:10px;" />
<img align="left" alt="HTML5" width="36px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" style="padding-right:10px;" />
<img align="left" alt="CSS3" width="36px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" style="padding-right:10px;" />
<img align="left" alt="Sass" width="36px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sass/sass-original.svg" style="padding-right:10px;" />
<img align="left" alt="GraphQL" width="36px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/graphql/graphql-plain.svg" style="padding-right:10px;" />
<img align="left" alt="MongoDB" width="36px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" style="padding-right:10px;" />
<img align="left" alt="MySQL" width="36px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" style="padding-right:10px;" />
<img align="left" alt="Git" width="36px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" style="padding-right:10px;" />
<img align="left" alt="GitHub" width="36px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" style="padding-right:10px;" />
<img align="left" alt="GitLab" width="36px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/gitlab/gitlab-original-wordmark.svg" style="padding-right:10px;" />
<img align="left" alt="BitBucket" width="36px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bitbucket/bitbucket-original-wordmark.svg" style="padding-right:10px;" />

<br />
<br />

### Tips for conventional NodeJs based REST API Express App

- Configure Typescript environment.
- Migrate all JS files to TS files.
- De-structure `server.ts` file into mini-apps. ( using [express.Router](https://expressjs.com/en/guide/routing.html).
  - create routes folder and each file has it’s own mini-app ( express.Router ).
  - controllers folder should have corresponding controller file for business logic.
- Convert mongoose models to TS with JSDoc/TSDoc comments.
- By achieving all of above^^, codebase is ready to generate swagger API using [tsoa](https://github.com/lukeautry/tsoa) package.
- Use [JOI](https://github.com/sideway/joi) package for param validations in api routes. ( provide validations in utils folder ).
- Configure pipeline for linting and testing.

Note: All of the above new packages I mentioned are active and widely accepted by dev community.
