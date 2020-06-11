# PxyzAdmin
后台管理系统，集成最常用、最基础的功能。



## 框架技术

- Springboot 2.0 
- Spring Security 实现登录认证；角色&权限交于系统本身程序控制（菜单持有制）
- Mybatis：JPA与Mybatis抉择了一下，还是使用Mybatis，自己写SQL感觉比较舒服
- MySQL
- Layui

## 目前功能

- 用户管理
- 菜单管理
- 角色管理

## 正在开发

- 基本信息 & 修改密码
- 角色管理-用户授权
- 用户管理-密码重置
- ip白名单
- 监控管理：读取服务器当前各项性能参数（oshi-core）
- 字典管理
- 登录日志
- 清理缓存按钮：这个计划使用redis存储用户菜单时使用。

## 前端模板

- 前端模板使用了

[https://github.com/zhongshaofa/layuiminilayuimini]: 

的模板，十分感谢，提供了一个很好的思路去管理这么多的前端组件；因为我本身在其基础上更新了一些组件的版本和代码，如果大家有需要最新的前端模板，可以点击链接自行获取layuimini项目。

- 更新了treeTable版本。
- 基于前后端开发，新增了common.js，其中更新在项目使用到的基础方法。

## 部署

1. 修改数据库配置（application.yml-->[-test,-dev,-pro]）
2. 在数据库中运行pxyz-admin.sql文件，目录：PxyzAdmin/pxyzadmin.sql

## 演示地址

admin.pxyz.top/index

## 系统截图

