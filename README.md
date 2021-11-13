# cra-template-ts-eslint-prettier

React template in TypeScript preconfigured with Eslint and Prettier. The base project was created with `create-react-app` using the typescript template using the command [`npx create-react-app my-app --template typescript`](https://create-react-app.dev/docs/adding-typescript/).

## Install

```zsh
npx create-react-app my-app --template @dany-eduard/cra-template-ts-eslint-prettier
```

> You must install the packages after installing. Use `npm i` or `yarn install`

## Git Clone

```zsh
git clone https://github.com/dany-eduard/cra-template-ts-eslint-prettier.git
```

## Eslint Rules

- [`import/extensions`: Ensure consistent use of file extension within the import path](https://github.com/import-js/eslint-plugin-import/blob/main/docs/rules/extensions.md)
- [`import/no-extraneous-dependencies`: Forbid the use of extraneous packages](https://github.com/import-js/eslint-plugin-import/blob/main/docs/rules/no-extraneous-dependencies.md)
- [`react/jsx-filename-extension`: Restrict file extensions that may contain JSX](https://github.com/yannickcr/eslint-plugin-react/blob/master/docs/rules/jsx-filename-extension.md)
- [`react/jsx-props-no-spreading`: Disallow JSX props spreading](https://github.com/yannickcr/eslint-plugin-react/blob/master/docs/rules/jsx-props-no-spreading.md)
- [`react/function-component-definition`: Enforce a specific function type for function components](https://github.com/yannickcr/eslint-plugin-react/blob/master/docs/rules/function-component-definition.md)
- [`no-use-before-define`: Disallow the use of variables before they are defined](https://eslint.org/docs/rules/no-use-before-define)
- [`@typescript-eslint/no-use-before-define`: Disallow the use of variables before they are defined](https://github.com/typescript-eslint/typescript-eslint/blob/master/packages/eslint-plugin/docs/rules/no-use-before-define.md)
- [`react/react-in-jsx-scope`: Prevent missing React when using JSX](https://github.com/yannickcr/eslint-plugin-react/blob/master/docs/rules/react-in-jsx-scope.md)

## Prettier Rules

- [`printWidth`](https://prettier.io/docs/en/options.html#print-width): `120`
- [`semi`](https://prettier.io/docs/en/options.html#semicolons): `false`
- [`singleQuote`](https://prettier.io/docs/en/options.html#quotes): `true`
- [`tabWidth`](https://prettier.io/docs/en/options.html#tab-width): `2`
- [`trailingComma`](https://prettier.io/docs/en/options.html#trailing-commas): `es5`
- [`useTabs`](https://prettier.io/docs/en/options.html#tabs): `false`

## Learn More

You can learn more about **Custom Templates** in the [Create React App dev documentation](https://create-react-app.dev/docs/custom-templates).
