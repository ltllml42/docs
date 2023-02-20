# 简短说明



<center><font face="宋体" size=12 color=green>cap-hr</font></center>

<center><font face="宋体">基于SpringBoot、springSecurity、Mybatis、Jwt、Vue的</font></center>
<center><font face="宋体">在此基础上增加了元数据管理，多数据源，工作流等应用</font></center>



> [!NOTE]
>
> 该平台结合了多家技术之所长，并和目前已知的快速开发平台做了对比，选定了在若依上进行实践的产物，其并不只是一套后台管理系统，
>
> 而是基于一个理念，在其平台上进行实践，更像是一个体系，可将其转移到任何Java平台上。

**cap-hr**  是一个基于RuoYi平台的 Java EE 企业级快速开发平台，基于经典技术组合（Spring Boot、Spring Security、MyBatis、Jwt、Vue），在RuoYi平台的基础上，进行深度改造与人事系统的基本业务结合,重写了底层架构和部分系统模块具体区别如下表所示



| 模块名称     | Royi平台     | cap-hr         |                                                              |
| :----------- | :----------- | :------------- | :----------------------------------------------------------- |
| 权限管理     | 一员管理     | 三员管理       | 变动改造                                                     |
| 日志管理     | 日志管理     | 日志管理       | 改造                                                         |
| 审计日志     | 无           | 审计日志       | 添加                                                         |
| 机构管理     | 机构管理     | 机构管理       | 重写（增加任务属性）                                         |
| 岗位管理     | 岗位管理     | 职务职级管理   | 重写（增加岗位属性）                                         |
| 数据权限     | 数据权限     | 数据权限       | 重写（根据业务进行重写）                                     |
| 菜单按钮授权 | 菜单按钮授权 | 菜单按钮授权   | 沿用                                                         |
| 多数据源     | 自研多数据源 | 多数据源       | 使用**[dynamic-datasource-spring-boot-starter](https://gitee.com/baomidou/dynamic-datasource-spring-boot-starter)** |
| 分布式事务   | 无           | 支持           | 1.支持atomiks<br />  2.seata-server                          |
| 代码生成     | 有           | 有             | 改造增加模板                                                 |
| 元数据管理   | 无           | 自研元数据管理 | Mybatis-plus上进行更新                                       |
| 全文检索     | 无           | 有             | Elasticsearch                                                |
| 导入导出     | 有           | 有             | Royi使用的是自研的，更改为 easy-poi                          |
| pdf          | 无           | 有             |                                                              |
|              |              |                |                                                              |









