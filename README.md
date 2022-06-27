<p align='center'>
简单的<sup><em>webpack-vue3</em></sup> 创建 Web 应用
<br> 
</p>

<br>

<br>

## 特性

- 🪐 [Vue 3](https://github.com/vuejs/vue-next), [wepack@5](https://webpack.js.org/), [pnpm](https://pnpm.js.org/),减小node_modules体积

<!-- - 🗂 [基于文件的路由](./src/pages) -->

- 📦 [组件自动化加载](./src/components)

- 🍍 [使用 Pinia 的状态管理](https://pinia.esm.dev/)

- 🎨 [UnoCSS](https://github.com/unocss/unocss) - 高性能且极具灵活性的即时原子化 CSS 引擎

- 😃 [各种图标集为你所用](https://github.com/antfu/unocss/tree/main/packages/preset-icons)

- 🌍 [I18n 国际化开箱即用](./locales)

- 🔥 使用 [新的 `<script setup>` 语法](https://github.com/vuejs/rfcs/pull/227)

- 📥 [API 自动加载](https://github.com/antfu/unplugin-auto-import) - 直接使用 Composition API 无需引入

- 🦔 可以自行引入 [critters](https://github.com/GoogleChromeLabs/critters) 的生成关键 CSS

- 🦾 TypeScript, 当然

- ☁️ 零配置部署 Netlify

<br>

## 预配置

### UI 框架

- [UnoCSS](https://github.com/antfu/unocss) - 高性能且极具灵活性的即时原子化 CSS 引擎

### Icons

- [Iconify](https://iconify.design) - 使用任意的图标集，浏览：[🔍Icônes](https://icones.netlify.app/)
- [UnoCSS 的纯 CSS 图标方案](https://github.com/antfu/unocss/tree/main/packages/preset-icons)

### 插件

- [Vue Router](https://github.com/vuejs/vue-router)
- [Pinia](https://pinia.esm.dev) - 直接的, 类型安全的, 使用 Composition api 的轻便灵活的 Vue 状态管理
- [Vue I18n](https://github.com/intlify/vue-i18n-next) - 国际化

### 编码风格

- 使用 Composition API 地 [`<script setup>` SFC 语法](https://github.com/vuejs/rfcs/pull/227)
- [ESLint](https://eslint.org/) 配置为 [@antfu/eslint-config](https://github.com/antfu/eslint-config).

### 开发工具
- [TypeScript](https://www.typescriptlang.org/)
- [Cypress](https://cypress.io/) - E2E 测试
- [pnpm](https://pnpm.js.org/) - 快, 节省磁盘空间的包管理器
- [Netlify](https://www.netlify.com/) - 零配置的部署
- [VS Code 扩展](./.vscode/extensions.json)
  - [Volar](https://marketplace.visualstudio.com/items?itemName=johnsoncodehk.volar) - Vue 3 `<script setup>` IDE 支持
  - [Iconify IntelliSense](https://marketplace.visualstudio.com/items?itemName=antfu.iconify) - 图标内联显示和自动补全
  - [i18n Ally](https://marketplace.visualstudio.com/items?itemName=lokalise.i18n-ally) - 多合一的 I18n 支持
  - [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)

## Git 提交规范

- 参考 [vue](https://github.com/vuejs/vue/blob/dev/.github/COMMIT_CONVENTION.md) 规范 ([Angular](https://github.com/conventional-changelog/conventional-changelog/tree/master/packages/conventional-changelog-angular))

  - `feat` 增加新功能
  - `fix` 修复问题/BUG
  - `style` 代码风格相关无影响运行结果的
  - `perf` 优化/性能提升
  - `refactor` 重构
  - `revert` 撤销修改
  - `test` 测试相关
  - `docs` 文档/注释
  - `chore` 依赖更新/脚手架配置修改等
  - `workflow` 工作流改进
  - `ci` 持续集成
  - `types` 类型定义文件更改
  - `wip` 开发中


## 当然，非常推荐大家使用vite

由于这个模板的业务场景非常的局限，下面提供了一个精心策划的列表，列出了社区维护的具有不同偏好和功能集的衍生项目。也可以看看他们。当然也欢迎你 PR 提供自己的项目！

[**vite**](https://github.com/vitejs/awesome-vite#templates) - Awesome Vite.js

> A curated list of awesome things related to Vite.js


## 现在可以试试!

> enalpro 需要 Node 版本 >=14

### 克隆到本地

如果您更喜欢使用更干净的 git 历史记录手动执行此操作

```bash
npx degit rwerplus/enalpro my-app
cd my-app
pnpm i # 如果你没装过 pnpm, 可以先运行: npm install -g pnpm
```

## 清单

使用此模板时，请尝试按照清单正确更新您自己的信息

-  *在 `LICENSE` 中改变作者名*
-  *在 `App.vue` 中改变标题*
-  *在 `vue.config.ts` 更改主机名*
-  *在 `public` 目录下改变favicon*
-  *移除 `.github` 文件夹中包含资助的信息*
-  *整理 README 并删除路由*

紧接着, 享受吧 ;/

## 使用

### 开发

只需要执行以下命令就可以在 http://localhost:3333 中看到

```bash
pnpm dev
```

### 构建

构建该应用只需要执行以下命令

```bash
pnpm build
```

然后你会看到用于发布的 `dist` 文件夹被生成。

## 相关仓库

<!-- ## 后台整合示例
