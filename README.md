#   Fast-Nest

帮助你快速初始化基于Nest.js的node后端服务

>   本项目适用：
>   -   node简易应用初始化
>   -   node项目初学试验
>   -   有兴趣的童鞋亦可作为项目脚手架(项目内都是基础功能与结构，是可以作为简单的脚手架的)

##  食用前

-   希望使用者有JavaScript基础，熟悉typescript更佳。
-   希望有简单node应用开发基础(可选)
-   希望能先了解Nest.js框架([传送门](https://github.com/nestjs/nest))

##  如何启动项目


```bash
git clone https://github.com/mykurisu/fast-nest.git

cd fase-nest

npm install

npm start
```

如代码所示，将本项目克隆至本地，安装好依赖即可启动服务，默认端口为**9999**，倘若需要调整请在根目录的**config.ts**中进行调整。

项目启动后，如果你没有启动本地的MongoDB会出现超时的报错，这时有两种方案：

①   将**common.module**中的mongo公共服务挂载删除

②   本地启动MongoDB，连接数据库的配置亦在**config.ts**内

##  这个项目内有什么料

-   [x] 一套可运行的nest项目代码(废话)
-   [x] 小而全的Node项目目录结构
-   [x] 按照核心、功能以及公共三个维度进行模块划分
-   [ ] 核心模块
    -   [x] 内置格式化返回数据的拦截器
    -   [x] 内置格式化返回错误信息的过滤器
    -   [x] 内置简易日志中间件
-   [ ] 公共模块
    -   [x] 内置MongoDB初始化服务
    -   [x] 内置腾讯云静态储存初始化服务
-   [ ] 功能模块
    -   [x] 内置简易用户信息获取模块
    -   [x] 内置文件上传模块(支持上传到腾讯云)
-   [ ] 打包发布

##  有关项目的开发实录

(待补充)

##  最后

如果对大家有帮助，不妨为我点个star。该项目会长期维护，争取成为真正的应用脚手架。
