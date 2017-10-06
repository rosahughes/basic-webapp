# basic-webapp

> A Vue.js project

## Build Setup
1. In the terminal, run the command `vue --version` to check the version of view installed. If vue is not installed, run the command `npm install -g vue-cli`.
2. Bootstrap the project skeleton with webpack framework by running the command `vue init webpack basic-webapp` (Note: you can replace `basic-webapp` with whatever name you choose for the application.) Answer the prompt questions, including standalone build and no additional frameworks.
3. Install dependencies using the command `npm install`. Run in a test environment on localhost:8080 with the command `npm run dev`.
4. Modify the template, script, and style in the `src/components/Hello.vue` file.
5. Create a Git repository, and follow the directions to create a new repository from files on the command line, adding all files instead of a README.md with the command `git add -A` in place of `git add README.md`. Commit and push changes to Github.
6. Configure Webpack to build files into the `docs/` directory in the `config/index.js` file. Change the path from `dist` to `docs` and set `assetsPublicPath` to `''`.
7. Build for production with minification using the command `npm run build`. Any errors will appear in the console. Commit and push changes to Github. 
8. From the Github repository homepage, go to "Settings" and in the "GitHub Pages" area, set the Source to master branch /docs folder, and save.

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
