## 环境搭建

1. 安装git客户端工具，熟练掌握git常用命令，诸如pull，push，stash，branch等。
2. 通过gitlab下载前端源码 http:\/\/112.124.34.33:10080\/ （需要申请加入）。

3. 安装[node](https://nodejs.org/en/)

4. 安装ember-cli，打开命令行窗口，输入 `npm install ember-cli –g`

5. 安装bower，输入 `npm install bower –g`

6. 在命令行窗口中切换到项目中

7. 执行`npm install`（需要翻墙或者修改npm中央仓库地址）

8. 接着`bower install`

9. 依赖安装完成后，启动项目，运行 `ember s --proxy=代理地址`  代理地址需咨询你所在小组master


## Ember

Ember官网（http:\/\/emberjs.com\/）

在搭建完成Ember-Cli环境后，可前往Ember官网查看基础教程（https:\/\/guides.emberjs.com\/v1.13.0\/）

（注关于Guides的版本，目前项目内选用的是1.13,但也可以选择以2.X的版本查看,2.X版本的文档相对更趋于完善）

需要了解的相关概念有

**对象模型\(重要\)**

 主要是Ember内建的一些功能，是构成整个Ember应用的基石，包括

 1.类继承 extend

 2.类混合 mixin

 3.类重写 reopen

 4.计算属性 computed

 5.观察器 observer

 6.绑定 binding

**组件\(重要\)**

 主要为Ember对于Web-Component的一种实现，包括组建作用域隔离,组建与外界Control\/Route的交互等

**模板**

 主要了解Ember对于模板内建的Helper，如Each等，主要是对于Handlebar模板语言的了解

**控制器\(重要\)**

 一种MVC职责划分,主要负责处理数据的交互逻辑

**路由\(重要\)**

 Ember内建的路由库，Ember有约定大于配置的理念，对于路由，有许多的约定。根据路由生成对应的控制器等。需要着重了解。

 （https:\/\/guides.emberjs.com\/v1.13.0\/getting-started\/naming-conventions\/）

附Ember相关资料:

Ember Teach\( http:\/\/emberteach.ddlisting.com\/ \)



## Ember-cli

....

