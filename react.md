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
[redux](https://github.com/reactjs/redux) 状态管理框架  
[redux-thunk](https://github.com/gaearon/redux-thunk) Thunk 中间件

[react-redux](https://github.com/reactjs/react-redux) react 绑定 redux

[reselect](https://github.com/reactjs/reselect) 对象选择器

[react-router](https://github.com/reactjs/react-router) 页面内路由

[react-router-redux](https://github.com/reactjs/react-router-redux) react-router 同步 redux

[redux-devtools](https://github.com/gaearon/redux-devtools) 支持工具

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

##fetch
[isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) 数据存取框架

[falcor](https://github.com/Netflix/falcor) 数据存取框架

[bookshelf](https://github.com/tgriesser/bookshelf) ORM 框架（MySQL and SQLite）

```
npm install --save isomorphic-fetch es6-promise

npm install falcor --save
npm install falcor-router --save

// ORM 框架
npm install knex --save
npm install bookshelf --save
// MySQL 驱动
npm install mysql --save
```

##lodash
[lodash](https://github.com/lodash/lodash) 通用函数库

[ramda](https://github.com/ramda/ramda) 函数式支持

```
npm install lodash --save

npm install ramda --save
```

##promise
[bluebird](https://github.com/petkaantonov/bluebird) 异步支持库

```
npm install bluebird --save
```

##immutable
[immutable](https://github.com/facebook/immutable-js) 不变数据集合

```
npm install immutable --save
```

##mocha + chai + sinon
[enzyme](https://github.com/airbnb/enzyme) React 测试框架

[mocha](https://github.com/mochajs/mocha) BDD 测试框架

[chai](https://github.com/chaijs/chai) BDD 断言框架  
[dirty-chai](https://github.com/prodatakey/dirty-chai)

[sinon](https://github.com/sinonjs/sinon) mocks 框架


##eslint
[eslint](https://github.com/eslint/eslint) 代码规范管理

[code style](https://github.com/airbnb/javascript) 代码风格约定

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

##sails
[sails](https://github.com/balderdashy/sails) 应用服务器 (基于 Node.js, Connect, Express, and Socket.io)

```
sudo npm install sails --save
```

##koa
[koa](https://github.com/koajs/koa) 应用服务器

```
sudo npm install koa --harmony-generators --save
```

##electron
[electron](https://github.com/atom/electron) 桌面应用开发框架

```
sudo npm install electron-prebuilt --save-dev
```
