---
Neo4j sql文件相关说明
---

1  本文件夹中保存了图数据库建库的的相关代码文件，一共分为create_location、create_is_from、create_study_at、create_work_at四个文件
  * create_location文件保存了构建行政地区的相关代码
  * create_is_from文件保存了构建出生地关系的相关代码
  * create_study_at文件保存了构建学习经历的相关代码
  * create_work_at文件保存了构建工作经历的相关代码

2 相关csv文件都存放在公司服务器中，地址为ftp://opsrv.mapout.lan/public/。

3 本项目所使用的图数据库版本是neo4j-community-3.3.1-windows。

4 使用方法：登录到Neo4j服务器，然后在浏览器的命令行中输入相应文件中的代码。
