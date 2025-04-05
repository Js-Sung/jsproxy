# jsproxy
jsproxy(cloudflare pages版)

![Image](useless/1.png)

## 简介
传统的jsproxy默认是搭建在cloudflare workers上的，但是workers的域名workers.dev在国内体验不好，e而cloudflare pages的域名pages.dev没问题，因此做简单修改将jsproxy搭建到cloudflare pages上。

## 使用
下载本仓库中的_worker.js并压缩为zip，新建cloudflare pages项目并上传zip文件。

## 参考
- [jsproxy](https://github.com/EtherDream/jsproxy/tree/master/cf-worker)
