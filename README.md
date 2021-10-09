<p align="center">
  <a href="">
    <img width="140" src="https://avatars.githubusercontent.com/u/73879334?s=200&v=4" />
  </a>
</p>

<h1 align="center">Action TypeScript Template</h1>
<div align="center">
A typescript template for rapid development of GitHub actions.
</div>

![](https://img.shields.io/github/workflow/status/actions-cool/action-ts-template/CI?style=flat-square)
[![](https://img.shields.io/badge/marketplace-action--ts--template-blueviolet?style=flat-square)](https://github.com/marketplace/actions/action-ts-template)
[![](https://img.shields.io/github/v/release/actions-cool/action-ts-template?style=flat-square&color=orange)](https://github.com/actions-cool/action-ts-template/releases)

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

## ⚡ Feedback

You are very welcome to try it out and put forward your comments. You can use the following methods:

- Report bugs or consult with [Issue](https://github.com/actions-cool/action-ts-template/issues)
- Submit [Pull Request](https://github.com/actions-cool/action-ts-template/pulls) to improve the code of `action-ts-template`

也欢迎加入 钉钉交流群

![](https://github.com/actions-cool/resources/blob/main/dingding.jpeg?raw=true)

## LICENSE

[MIT](https://github.com/actions-cool/action-ts-template/blob/main/LICENSE)
