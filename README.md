# 极客时间ServerLess专栏，"待办任务"后端项目

这个项目用 Node.js框架[Express.js](http://expressjs.com/en/4x/api.html#express)开发，主要代码在index.js中。
这个仓库是后端项目代码，这个版本TodoList的数据放在内存中。

## 环境准备

安装 Node.js依赖包 `node_modules`:

```bash
npm install
```

or

```bash
yarn
```

## 提供脚本

我们将提供你几个常用脚本，具体脚本放在 `package.json`。

### 启动项目

```bash
npm start
```
启动后，你可以通过浏览器地址栏：<http://127.0.0.1:3000>访问你的本地代码；
### 构建项目

```bash
npm run build
```

### 检查代码规范

```bash
npm run lint
```

你也可以检查代码规范并自动修复代码规范错误:

```bash
npm run lint:fix
```

### 测试代码

```bash
npm test
```
