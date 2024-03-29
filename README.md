# Ingeniero Alejandro Rangel

[![Custom Badge][badge-shields]][url-badge]
[![node][badge-node]][url-node]
[![npm][badge-npm]][url-npm]
[![JavaScript][badge-js]][url-js]
[![TypeScript][badge-ts]][url-ts]
[![React][badge-react]][url-react]
[![Redux][badge-redux]][url-redux]
[![SASS][badge-sass]][url-sass]
[![i18n][badge-i18n]][url-i18n]
[![StoryBook][badge-storybook]][url-storybook]
[![Jest][badge-jest]][url-jest]
[![webpack][badge-webpack]][url-webpack]

[![Ingeniero Alejandro Rangel][gif-app]][url-docs]

> APP Description

## ENVIRONMENTS

All pipelines and deployments are managed for the [fury][url-fury] application, where the following environments are found:

| SCOPE  | URL                                              | CONFIG                                                                                                                         |
| ------ | ------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------ |
| dev    | <https://path part/>                             | [dev.js][config-dev]                                                                                                           |
| stage  | <https://path part/>                             | [stage.js][config-stage]                                                                                                       |
| prod   | <https://path part/>                             | [default-production.js][config-prod]                                                                                           |

The variants of each url are configured in the [routes][config-routes] file.

The deeplinks have a documentation on [workplace][docs-deeplink] and in the documentation of [mobile][docs-mobile].

- Usually double quotes should be encoded as %20, some encoders pass it as %E2%80%9D and this can break the deeplink


The aforementioned URLs need to be complemented with a path comprised of the following attributes:

1. **PATH**: `path`
2. **Attributes**: The attributes primarily depend on the path, but for this example, several keys related to values of different types (numeric, text, object) are used.

   ```json
   attributes
   ```

3. **Complete URL**: With the aforementioned information, the complete and encoded URL should be constructed, resulting in the following format: <https://compl url example>

**NOTE**: The URL must be encoded. This can be achieved using an [online tool][url-decode].

## FEATURES TOGGLE

The following FTs can be consulted in detail with the help of the following curl


|  changed   | lists | sites | ranges | business | platform | name        | changed_by   |
| :--------: | :---: | :---: | :----: | :------: | :------: | ----------- | ------------ |
| 2021-10-12 |       |       |        |          |          | mobile-chat | fmonasteriom |

**Note:** This must be migrate to [Feature Flags][docs-FF], here more documentation.

## GITHUB CONSIDERATIONS

On our [website][url-site-github], you can find documentation about GitHub configuration and the templates implemented in this software.

## React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

### Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type aware lint rules:

- Configure the top-level `parserOptions` property like this:

```js
   parserOptions: {
    ecmaVersion: 'latest',
    sourceType: 'module',
    project: ['./tsconfig.json', './tsconfig.node.json'],
    tsconfigRootDir: __dirname,
   },
```

- Replace `plugin:@typescript-eslint/recommended` to `plugin:@typescript-eslint/recommended-type-checked` or `plugin:@typescript-eslint/strict-type-checked`
- Optionally add `plugin:@typescript-eslint/stylistic-type-checked`
- Install [eslint-plugin-react](https://github.com/jsx-eslint/eslint-plugin-react) and add `plugin:react/recommended` & `plugin:react/jsx-runtime` to the `extends` list

## License

© 2023 Alejandro Rangel

[badge-i18n]: https://img.shields.io/badge/-i18next-26A69A?style=plastic&logo=i18next&labelColor=black
[badge-jest]: https://img.shields.io/badge/-29.6.2-C21325?logo=jest&logoColor=C21325&labelColor=white
[badge-js]: https://img.shields.io/badge/-JavaScript-F7DF1E?style=plastic&logo=javascript&labelColor=black
[badge-node]: https://img.shields.io/badge/-14.17.3-036e02?style=plastic&logo=nodedotjs&labelColor=333
[badge-npm]: https://img.shields.io/badge/-6.14.15-CB3837?style=plastic&logo=npm&labelColor=white
[badge-react]: https://img.shields.io/badge/-18.2.0-61DAFB?style=plastic&logo=react&labelColor=23272f
[badge-redux]: https://img.shields.io/badge/-4.0.0-764ABC?style=plastic&logo=redux&logoColor=764ABC&labelColor=white
[badge-sass]: https://img.shields.io/badge/-1.63.4-CC6699?style=plastic&logo=sass&labelColor=black
[badge-shields]: https://img.shields.io/badge/Shields-IO-555?labelColor=96c901
[badge-storybook]: https://img.shields.io/badge/-7.0.26-FF4785?style=plastic&logo=storybook&labelColor=white
[badge-ts]: https://img.shields.io/badge/-4.9.5-3178C6?style=plastic&logo=typescript&labelColor=black
[badge-webpack]: https://img.shields.io/badge/-5.88.2-8DD6F9?style=plastic&logo=webpack&labelColor=2B3A42
[gif-app]: ./docs/assets/img/app.gif
[url-badge]: https://shields.io/
[url-decode]: https://www.urldecoder.org/
[url-docs]: https://furydocs.io/Repo/latest/#/
[url-jest]: https://jestjs.io/es/
[url-js]: https://www.javascript.com/
[url-node]: https://nodejs.org/es
[url-nordic]: https://nordic.adminml.com/
[url-npm]: https://www.npmjs.com/
[url-react]: https://reactjs.org/
[url-redux]: https://redux.js.org/
[url-sass]: https://sass-lang.com/
[url-storybook]: https://storybook.js.org/
[url-ts]: https://www.typescriptlang.org/
[url-webpack]: https://webpack.js.org/
