## React-Cnode

> react web app, api 由 **cnode社区** 提供，欢迎大家star和fork

###  技术栈
react + react-router + axios + mobx + mobx-react + antd-mobile

###  demo
##### ps: 暂时没有提高live demo，见谅
![images](https://user-images.githubusercontent.com/23744602/31574427-40b147f2-b102-11e7-8731-253ab286dc37.gif)


## 目录结构
```
react-cnode/
   |
   ├──icons/                    * 用到的icon
   |
   ├──components/               * 可复用组件
   │
   │──pages/                    * 展示的页面
   |
   ├──store/                    * mobx
   │
   ├──router                    * 路由
   |
   ├──routes/                   * 路由的配置，动态加载
   │
   │──axios/                    * axios的配置文件
   │
   │──utils/                    * 工具函数
   │    |
   |    |—— db.js               * localstorage操作
   |    |
   |    |__ index.js            * 别的工具函数
   │
   │ 
   │——constants/                * 一些常量(其实没怎么用)
   │
   │
   │
   │──index.css                 * 全局的样式，其中也有修改了ant-mobile的样式
   │__index.js                  * 入口文件
```


### TODO

- ~~消息~~

- ~~用mobx重构~~

### 如何启动
Step 1
```
git clone git@github.com:Juliiii/React-Cnode.git
```

Step 2
```
npm i
```

Step 3
```
npm start
```
#### license

No license
