# SpringCloud config
## 1.简介
使用springCloud config组件，实现项目配置文件统一和动态化配置

## 2.实现步骤
**microservicecloud**  
- 仓库地址：https://github.com/HeTreeTerr/microservicecloud.git
- config-3344子项目负责读取microservicecloud-config中的配置文件内容，
为其它服务提供基础
- config-3355子项目从3344中读取配置，以读取到的配置为基础启动服务

**microservicecloud-config**  
- 仓库地址：https://github.com/HeTreeTerr/microservicecloud-config.git
（本仓库自身）
- *.yml存放在git上，可以将配置文件和项目代码隔离，增加安全和保密性
