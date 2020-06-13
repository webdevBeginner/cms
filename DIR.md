目录结构

├── README.md 项目介绍

├── index.html 入口页面

├── build 构建脚本目录

│ ├── build-server.js 运行本地构建服务器，可以访问构建后的页面

│ ├── build.js 生产环境构建脚本

│ ├── dev-client.js 开发服务器热重载脚本，主要用来实现开发阶段的页面自动刷新

│ ├── dev-server.js 运行本地开发服务器

│ ├── utils.js 构建相关工具方法

│ ├── webpack.base.conf.js wabpack 基础配置

│ ├── webpack.dev.conf.js wabpack 开发环境配置

│ └── webpack.prod.conf.js wabpack 生产环境配置

├── config 项目配置

│ ├── dev.env.js 开发环境变量

│ ├── index.js 项目配置文件

│ ├── prod.env.js 生产环境变量

│ └── test.env.js 测试环境变量

├── mock mock 数据目录

│ └── hello.js

├── package.json npm 包配置文件，里面定义了项目的 npm 脚本，依赖包等信息

├── src 源码目录

│ ├── main.js 入口 js 文件

│ ├── app.vue 根组件

│ ├── components 公共组件目录

│ │ └── title.vue

│ ├── assets 资源目录，这里的资源会被 wabpack 构建

│ │ └── images

│ │ └── logo.png

│ ├── routes 前端路由

│ │ └── index.js

│ ├── store 应用级数据（state）

│ │ └── index.js

│ └── views 页面目录

│ ├── hello.vue

│ └── notfound.vue

├── static 纯静态资源，不会被 wabpack 构建。

└── test 测试文件目录（unit&e2e）

└── unit 单元测试

    ├── index.js            入口脚本

    ├── karma.conf.js          karma配置文件

    └── specs              单测case目录

      └── Hello.spec.js
