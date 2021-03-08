# 人事管理系统
包括：
* 系统管理
* 部门管理
* 职位管理
* 员工管理
* 公告管理

开发技术：
* Java EE 架构：SSM（Spring + Spring MVC + MyBatis）框架
* 表现层技术：JSP
* 前端框架：easyUI
* 项目管理工具：Maven
* 数据库：MySQL

本系统采用的是 Java EE 分层结构：
1. 表现层：JSP 页面
2. MVC 控制器层：Spring MVC 技术，由一系列控制器组成。
3. 业务逻辑层：Spring 技术，由一系列的业务逻辑对象组成。
4. DAO 层：MyBatis 框架，由一系列的 DAO 组件组成，这些 DAO 实现了对数据库的创建、查询、更新和删除（CRUD）等原子操作。
5. Domain Object 层：由一系列的 POJO（Plain Old Java Object，即普通的、传统的 Java 对象）组成，是一些简单的 Java Bean 类。
6. 数据库：MySQL 数据库，存储持久化数据。