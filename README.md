# HIS
## 简介
1、HIS 医院信息系统。包含功能模块：登陆、挂号、医生工作站、药房管理、缴费共四个模块  
2、本文档仅提供简要说明，如需详细使用说明及开发细节请移步WiKi  
3、出于安全考虑，已经移除/ver1.0/mysql.cs中的数据库连接信息    
   如果您需要进行二次开发，请下载Release中最新的数据库导入自己的服务器，将连接信息改为自己的连接信息，然后使用Visual Studio重新生成可执行文件。  
4、如果您只希望测试功能，请直接在Release中下载最新的可执行文件

## 技术声明
1、设计模式:C/S，客户端和云端数据库，数据库采用AWS的RDS服务提供的MySQL5.7  
2、开发平台:.Net Framework

## 许可证与版权声明
1、GPL许可证  
  
2、本项目为团队项目  
   团队成员友链：

## 版本与开发状态
一、版本号：ver1.0  
二、开发状态记录：  
    
    4/4/2020  
    完成了组件布局与界面美化
    
    4/5/2020
    登陆界面后台逻辑的实现：
    1、重写数据库连接公共类
    2、规范化变量命名，本工程统一采用小驼峰命名法
  


    
