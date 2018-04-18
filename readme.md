## 脚手架工具xgk

xgk是自动创建项目模块的脚手架工具,目前是基于管理端的项目结构去解析创建。

## 安装

- clone仓库

git clone ssh://git@git.sankuai.com/~zhouxiong03/xgk.git

- 进入到项目目录

cd xgk

- 安装依赖

npm install

- npm包链到本地

npm link

## 使用方法

xgk通过-m参数可以创建模块,包括对应的html,Controller,Service等文件,路由文件也会同时进行修改。

```
xgk -m 一级模块名/二级模块名
```
例如想在快驴驼峰的订单管理下新增一个订单回收站二级模块,可以通过以下命令完成。

```
xgk -m oms/recycleBin
```
然后就可以直接进行业务功能的编写了。
