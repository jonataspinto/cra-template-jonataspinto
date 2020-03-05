Esse é um template para [Create React App](https://github.com/facebook/create-react-app) com algumas dependências configuradas.

Você pode saber mais sobre custom-templates na [Documentação Oficial](https://create-react-app.dev/docs/custom-templates/)

## Como usar esse template?

Abra seu terminal e rode:
```shell
npx create-react-app YOUR_PROJECT_NAME --template jonataspinto-template
```
Isso criará um projeto com as seguintes libs:

* [axios](https://github.com/axios/axios)
* [plop](https://www.npmjs.com/package/plop)
* [polished](https://polished.js.org/)
* [prop-types](https://github.com/facebook/prop-types)
* [react-redux](https://redux.js.org/introduction/getting-started)
* [react-router-dom](https://reacttraining.com/react-router/web/guides/quick-start)
* [redux](https://redux.js.org/)
* [redux-thunk](https://github.com/reduxjs/redux-thunk)
* [styled-components](https://www.styled-components.com/)
* [styled-icons](https://github.com/jacobwgillespie/styled-icons)
* [styled-media-query](https://www.npmjs.com/package/styled-media-query)



> [IMPORTANTE] - dependencias de desenvolvimento (devDependencies) ainda não são suportadas no create-react-app templates. Portanto, se você deseja ter o ESLint e o Prettier configurados em seu projeto, siga as etapas abaixo:

```shell
# instalando devDependencies manualmente 
yarn add prettier eslint babel-eslint eslint-config-prettier eslint-plugin-prettier eslint-plugin-import-helpers -D
```
> No proximo ponto sugiro usar o famoso modelo da Airbnd.
```shell
# gerando o eslint.json 
yarn eslint --init
```

Sugestões de configuraçoes:

* [.eslintrc.json](https://gist.github.com/jonataspinto/74b2dbb540d05abbdb4e142cee992e2f)
* [.prettierrc](https://gist.github.com/jonataspinto/64e386614cdfa1b8d249a2b458e08a2d)
* [.editorconfig](https://gist.github.com/jonataspinto/66567d0530aba416d2ea4389e99d7605)

> [IMPORTANTE] - não se esqueça de instalar e ativar as extenssões de eslint e prettier no seu vsCode.

