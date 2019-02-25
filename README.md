【此为V免签监控端源码】

V免签  —— 个人开发者收款解决方案
===============


V免签 是基于SpringBoot 2.1.1 实现的一套免签支付程序，主要包含以下特色：

 + 使用H2-Database，仅需安装Java环境，简单配置，一键搭建
 + 超简单Api使用，提供统一Api实现收款回调
 + 免费、开源

> V免签的运行环境为JDK版本1.8。

> V免签仅供个人开发者调试测试使用，请勿用于非法用途，商用请您申请官方商户接口

## 安装

 + 下载已经编译好的war,位于GitHub的releases中
 + 确认本机已经拥有java的运行环境（JDK>=1.8）,如果没有，请您安装java的运行环境
 + 在war包的同级目录，在控制台输入启动命令 java -jar v.war
    + 请将v.war替换成您下载的war包的名字
    + 如果您需要自定义项目的运行端口，请您在启动的时候使用：java -jar v.war --server.port=9090 (9090可以替换成任意端口)
 + 打开浏览器，访问 localhost:8080
 + 点击系统设置，进入设置页面，修改系统的默认配置
 + 下载V免签监控端到安卓手机或安卓模拟器，开启辅助服务，实现收款回调功能
 + 默认管理账号为：admin
 + 默认通讯密钥为：admin
 + 保存配置后，即可开始使用


 > 升级说明：请您直接下载新版本覆盖旧版本即可！


## 说明
 + 请部署完成后访问后台，有详细的Api说明


## 注意

  + 本系统原理为监控收款后手机的通知栏推送消息，所以请保持微信/支付宝/V免签监控端后台正常运行，且添加到内存清理白名单！

## 更新记录
 + v1.1（2019.02.25）
   + 修复安卓7.0以上系统监控App闪退问题
   + 修复监控端检测服务状态无法正确检测是否正常问题
   + 添加商家码收款回调支持，商家码收款的也能正常回调啦

 + v1.0（2019.01.31）
   + 初版发布

## 版权信息

V免签遵循 MIT License 开源协议发布，并提供免费使用，请勿用于非法用途。


版权所有Copyright © 2019 by vone (http://szvone.cn)

All rights reserved。

