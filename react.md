#React 技术资源

##node
[node.js](https://nodejs.org) 服务器
 
```
node -p process.versions.v8
node -v
```
##npm
[npm.js](https://www.npmjs.com) 包管理

```
sudo npm install npm@latest -g
npm -v
```

然后，需要创建项目目录

```
mkdir MyProject
cd MyProject
npm init
npm install
```
##react
[react.js](https://github.com/facebook/react) 视图表现框架

```
npm install react --save
npm install react-dom --save
```
##redux
[redux.js](https://github.com/reactjs/redux) 状态管理框架

[react-redux](https://github.com/reactjs/react-redux) react 绑定 redux

[reselect](https://github.com/reactjs/reselect) 对象选择器

[react-router](https://github.com/reactjs/react-router) 页面内路由

[react-router-redux](https://github.com/reactjs/react-router-redux) react-router 同步 redux

```
npm install redux --save

// 绑定器
npm install react-redux --save

// 选择器
npm install reselect --save

// 路由器
npm install react-router --save

// 同步器
npm install react-router-redux --save
```
##relay
[relay.js](https://github.com/facebook/relay) 数据管理框架

```
npm install relay --save
```

##eslint
[eslint](https://github.com/eslint/eslint) 代码规范管理

```
npm install eslint -g
```
##babel
[babel](https://github.com/babel/babel) ES6 转换 ES5

```
npm install babel -g
```

##webpack
[webpack]() 打包及资源管理

```
npm install webpack -g
npm install webpack --save-dev

npm install eslint@2.x babel-eslint@next --save-dev
```