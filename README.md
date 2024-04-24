# Vue 3 + TypeScript + Vite

This template should help get you started developing with Vue 3 and TypeScript in Vite. The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

## Recommended Setup

- [VS Code](https://code.visualstudio.com/) + [Vue - Official](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (previously Volar) and disable Vetur

- Use [vue-tsc](https://github.com/vuejs/language-tools/tree/master/packages/tsc) for performing the same type checking from the command line, or for generating d.ts files for SFCs.

在package.json文件中

```json
"dev": "vite --open",
```

可以在使用npn run dev 的时候，自动打开浏览器

## 配置eslint

安装：
pnpm i eslint -D

生成配置:
npx eslint --init

安装vue校验插件
pnpm install -D eslint-plugin-import eslint-plugin-vue eslint-plugin-node eslint-plugin-prettier eslint-config-prettier eslint-plugin-node
@babel/eslint-parser

package.json 添加运行脚本

```json
"scripts":{
    "lint":"eslint src",
    "fix":"eslint src --fix"
}
```

使用pnpm run lint 校验代码
使用pnpm run fix 修复代码
