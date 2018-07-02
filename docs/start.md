# electron 快速开始

## 环境准备
 - electron是基于nodejs的所以首先需要安装nodejs
    - 直接安装：node.js官网地址[https://nodejs.org](https://nodejs.org) 
    - nvm管理多版本node.js：可以用nvm 进行node版本进行管理
        - windows系统安装nvm [https://github.com/coreybutler/nvm-windows](https://github.com/coreybutler/nvm-windows)
        - Mac系统安装nvm [https://github.com/creationix/nvm#manual-install](https://github.com/creationix/nvm#manual-install)
        - Ubuntu系统安装nvm [https://github.com/creationix/nvm](https://github.com/creationix/nvm)
- npm包管理工具
    - 安装好nodejs后npm包管理工具也会顺带手安装好，所以他不需要我们手动安装
- 安装Git环境
    - windows [http://msysgit.github.com/](http://msysgit.github.com/)
    - Mac [http://msysgit.github.com/](http://msysgit.github.com/)
    - Ubuntu apt-get install git

## 全局安装electron

```sh
# 安装electron
npm install -g electron

```
## 下载最简单的demo

```
# 克隆这仓库
  $ git clone https://github.com/electron/electron-quick-start
  # 进入仓库
  $ cd electron-quick-start
  # 安装依赖库
  $ npm install
  # 运行应用
  $ npm start
```
　　运行后就能看见一个简单的PC应用demo跑起来了，这时应用是在开发模式下运行的，还没有打包成平时我们看见的可执行文件，先别急，打包我们后面再讲，这一节先知道如何快速的搭建一个electron的开发环境。
