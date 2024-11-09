基于 Socket 的 HTTP 服务器和类 Flask MVC 框架
===========================================

- 基于 Socket 的 HTTP 服务器和类 Flask MVC 框架 是使用 Python 编写的 Web 框架。
- 技术栈：Python + Socket + MySQL + HTTP

![demo](https://github.com/noahwork/weblite-py/blob/main/weibo.gif)

功能
--------
 - 实现了 HTTP 协议的获取、解析、返回。
 - 通过 Socket 实现 HTTP 协议通信。
 - 通过多线程实现异步处理访问。
 - 控制层 Controller，通过路由字典进行路由分发，高阶函数进行权限验证，将 HTTP 请求和响应封装成对象。
 - 模型层 Model，基于 MySQL 的自制 ORM，动态拼接 SQL 语句进行表操作和表内数据的增删改查并封装。
 - 视图层 View，基于 Jinja2 的动态模板渲染，由 HTTP 服务器返回响应字节流。

反馈
-------------
 - 现在就在[issue](https://github.com/noahwork/weblite-py/issues)中提问。
