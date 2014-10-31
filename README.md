# 微智2014前端开发工作流

> 使用 [grunt-init][]创建基于seajs和less的前端开发工作流程.

[grunt-init]: http://gruntjs.com/project-scaffolding

## 什么是前端工作流
随着web的日益发展，前端的工作越来越繁多，使用的工具也越来越多

目前一个基本的web开发流程类似下面的结构

```
1、建立项目，梳理目录结构

2、coding...

3、发布
```

看起来很简单的流程，但是如果仔细考虑，就会碰到很多问题

```
1、线上资源和开发资源的更新问题，如何保证客户端载入的永远是线上最新的版本，而不使用缓存。

2、前端资源的压缩和打包，太繁杂，又要压缩js，又要压缩css，还要压缩图片，一个工作日，都不一定能处理好这些问题。

3、如果项目太大，如何形成良好的团队开发模式。
```

## 使用工作流解决问题

