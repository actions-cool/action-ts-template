<p align="center">
  <a href="">
    <img width="140" src="https://avatars.githubusercontent.com/u/73879334?s=200&v=4" />
  </a>
</p>

<h1 align="center">Action TypeScript Template</h1>
<div align="center">
A typescript template for rapid development of GitHub actions.
</div>

![CI](https://github.com/actions-cool/action-ts-template/workflows/CI/badge.svg)

## 🚀 How to use?

![](https://github.com/actions-cool/resources/blob/main/image/template.png?raw=true)

## 📒 Catalog Introduction

```
├── .github/workflows/     The CI for make sure it is packaged correctly
├── dist                   Package the generated Aciton execution code
├── src                    Component home directory
│   └── main.ts            Your code
├── .eslintrc.js           Eslint config
├── .prettierrc.js         Prettier config
├── action.yml             Action config
└── tsconfig.json          TypeScript config
```

The rest of the documents can be consulted by yourself.

## 🤖 Command introduction

| Name | Desc |
| -- | -- |
| build | ts build |
| format | prettier write |
| lint | eslint check |
| package | action build for release |
| all | npm all |

## MIT

https://github.com/actions-cool/action-ts-template/blob/main/LICENSE
