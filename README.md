# 基于区块链的学位认证管理系统

## 项目简介

学位造假现象对社会造成了严重的影响，而传统的学位认证系统认证繁琐、成本高。而SmartDegreeCertificate系统底层采用区块链技术，不易篡改的特性大大增加了系统的可信度。

项目使用微服务架构，主要语言为Java和Node，完整运行需要以下项目。

[DegreeCertificate-node](https://github.com/VNTChainUnit/DegreeCertificate-node)

[DegreeCertificate-java](https://github.com/VNTChainUnit/DegreeCertificate-java)

## 运行说明

- 下载/clone 两个项目源码
- 需要准备一个VNT账号，拥有一定VNT币
- 需要智能合约源码，并部署拿到智能合约地址
- 目前2.0还在开发阶段，暂时不能体验全部功能，可以查看基于Nodejs+Express的1.0版本。[DegreeCertification](https://github.com/VNTChainUnit/DegreeCertification)
- 开发完成后将会开发一键部署脚本。

## 技术架构

系统底层采用VNTChain智能合约，交互采用Vnt.js，表示层使用NodeJs+express架构，MongoDB存放用户账户信息。



