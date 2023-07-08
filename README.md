## **贪吃蛇练习**

使用 TypeScript + Webpack + Less 实现贪吃蛇的例子；

### **项目依赖**

TypeScript：

- typescript；
- ts-loader；

Webpack：

- webpack；
- webpack-cli；
- webpack-dev-server；
- html-webpack-plugin；
- clean-webpack-plugin；

Babel：

- core-js；
- babel-loader；
- @babel/core；
- @babel/preset-env；

Less & CSS 资源：

- style-loader；
- css-loader；
- less；
- less-loader；
- postcss；
- postcss-loader；
- postcss-preset-env；

### **项目使用**

#### **编译运行**

在确保已经正确安装 node 和 npm 的前提下：

分别执行下面的命令安装依赖并编译项目：

```bash
# 安装依赖
npm i
# 编译打包
npm run build
```

编译完成后，使用浏览器打开 dist 目录下的`index.html`即可游玩；

#### **继续开发**

使用`npm run start`进入开发模式；

默认使用 Chrome 浏览器打开，可以修改`package.json`中的值：

```json
{
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1",
    "build": "webpack",
    "start": "webpack serve --open chrome.exe"
  }
}
```
