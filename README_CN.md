# 软件环境
- NetBeans 8.2
- JDK8
- Hadoop2.5.0
- MySQL Server5.5

# 文件配置
1. 把`libs`添加到`WebApplication/web/WEB-INF/lib`中
2. 在MySQL中运行`shoppingdatabase.sql`
3. 修改`WebApplication/src/java/properties/database.properties`中的`username`和`password`为本地数据库用户名和密码
4. 修改`WebApplication/src/java/log4j.properties`中的`log4j.appender.file.File`属性，将其改为要存放日志的目录
5. 用NetBeans打开`WebApplication`，把`libs`添加到库文件中
6. 右键项目名-清理并构建，再通过右键`WebApplication/web/first/pages/HomePage.jsp`运行文件打开项目主页
