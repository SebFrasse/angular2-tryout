# Angular 2 QuickStart Source

This repository holds basically a master of the contents of the completed Angular2 Tutorial
"Tour-of-heroes". This means that npm installs have been completed and the code finished.
The intent is to build omn this base in trying to make something useful.

Initialize this project as a *local git repo* and make the first commit:
```bash
$ git init
$ git add .
$ git commit -m "Initial commit"
```

Create a *remote repository* for this project on the service of your choice.

Grab its address (e.g. *`https://github.com/<my-org>/my-proj.git`*) and push the *local repo* to the *remote*.
```bash
$ git remote add origin <repo-address>
$ git push -u origin master
```
### Start development

Install the npm packages described in the `package.json` and verify that it works:

```bash
$ npm install
$ npm start
```
You're ready to write your application.

Remember the npm scripts in `package.json`:

* `npm start` - runs the compiler and a server at the same time, both in "watch mode".
* `npm run tsc` - runs the TypeScript compiler once.
* `npm run tsc:w` - runs the TypeScript compiler in watch mode; the process keeps running, awaiting changes to TypeScript files and re-compiling when it sees them.
* `npm run lite` - runs the [lite-server](https://www.npmjs.com/package/lite-server), a light-weight, static file server, written and maintained by
[John Papa](https://github.com/johnpapa) and
[Christopher Martin](https://github.com/cgmartin)
with excellent support for Angular apps that use routing.
* `npm run typings` - runs the typings tool.
* `npm run postinstall` - called by *npm* automatically *after* it successfully completes package installation. This script installs the TypeScript definition files this app requires.
