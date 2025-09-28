# SkyBite
### A Multi-module Food Delivery Platform
模块化与分层架构：项目采用多模块设计（如 sky-common公共模块、sky-pojo实体模块、sky-server业务模块），实现了代码的高内聚低耦合，结构清晰，便于团队协作与维护。

前后端分离开发：采用当前主流的开发模式，后端提供RESTful API，前端（包括管理端和用户端）独立开发，并通过Nginx反向代理解决跨域问题，这种架构提升了开发效率和系统可扩展性。

技术栈全面：项目综合运用了Spring Boot、Spring MVC、MyBatis等主流框架，并引入了JWT令牌认证、Redis缓存、Spring Task定时任务等实用技术，覆盖了企业级应用开发的关键环节
