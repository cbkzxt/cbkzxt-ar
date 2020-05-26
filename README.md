# cbkzxt-ar

船舶控制-AR 工程

本工程分为三个部分：

- basic: 基础工程，通用类、组件在此实现
- scenes: 场景工程，包含所有的AR场景
- pwa: App工程，在此实现 船舶控制-AR PWA应用

## 初始化工程

> 注意！在 Windows 环境下，需首先执行：
> ```
> git config --global core.autocrlf false
> ```
> 用以确保 git 时不会自动生成 CRLF 换行符

```
git clone git@github.com:cbkzxt/cbkzxt-ar.git
cd ./cbkzxt-ar
npm run init-proj
```

## 构建工程

```
npm run build
```

## 启动服务

```
npm run server
```