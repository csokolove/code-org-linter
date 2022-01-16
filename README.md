# code-org-linter

ESLint files that follow the same styling guide as the [Code.org App Lab](https://code.org/educate/applab).

The linter can be used in both the browser and Node, however the [`code-org`](https://github.com/csokolove/code-org) library can only be used within [Node.js](https://nodejs.org).

The linter can also be used with TypeScript, you just need to install the [parser](https://www.npmjs.com/package/@typescript-eslint/parser):
```shell
npm i --save-dev typescript @typescript-eslint/parser
```

# Usage

1. Ensure an `npm` project has been initiated. If it hasn't, do so now:
```shell
npm init -y
```
(omit the -y flag to customize `package.json` options)

2. Duplicate an ESLint file from the `linter` directory in this repository.
3 formats are available:
* JS
* YAML
* JSON

3. Add the ESLint file to the root of your project

4. Run the `npx eslint {filename}` command (to lint a specific file) OR `npx eslint *` (to lint the entire project)


# code-org Library

Check out the [`code-org` library](https://github.com/csokolove/code-org) that allows you to use App Lab functions within Node.js!

# License

[MIT License](LICENSE)