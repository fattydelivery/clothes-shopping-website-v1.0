# Software Environment
- NetBeans 8.2
- JDK8
- Hadoop2.5.0
- MySQL Server5.5

# File configuration
1. Add `libs` to `WebApplication/web/WEB-INF/lib`.
2. Run `shoppingdatabase.sql` in MySQL.
3. Modify `username` and `password` in `WebApplication/src/java/properties/database.properties` to the local database username and password.
4. Modify the `log4j.appender.file.File` property in`WebApplication/src/java/log4j.properties` and change it to the directory where you want to store the logs.
5. Open `WebApplication` with NetBeans and add `libs` to the library file.
6. Right-click the project name-clean and build, then run the file by right-clicking `WebApplication/web/first/pages/HomePage.jsp` to open the project home page.