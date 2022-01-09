This is an example project that represents how to set up a Node.js commonjs project with
[Jasmine@4](https://github.com/jasmine/jasmine-npm) for [TypeScript](https://github.com/microsoft/TypeScript).

Key steps:
- add `@types/jasmine`, `@types/node` and `ts-node` to the dev dependencies `$ npm i --save-dev @types/jasmine ts-node @types/node`
- set `"type": "commonjs"` in the `package.json`
- create a [jasmine helper](jasmine-typescript-helper.js) that call `ts-node/register`
- register the helper in the `jasmine.json` config file
