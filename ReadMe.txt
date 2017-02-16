1  解压 apache-tomcat-8.0.32-windows-x64.zip
2  打开 apache-tomcat-8.0.32-windows-x64/conf/server.xml
3  查找 Connector port="8080" 此端口可以修改成自已喜欢的端口号。
4  查找 "Host Name" 并将 = 号后面的localhost改成本机IP地址。查找 defaultHost="localhost" 将其改成defaultHost="本机IP">>
5  新建环境变量 CATALINA_HOME 和 JAVA_HOME。CATALINA_HOME的值为 apache-tomcat-8.0.32-windows-x64解压文件存放目录。例如C:\apache-tomcat-8.0.32-windows-x64。JAVA_HOME值为jdk路径 （例如）C:\Program Files\Java\jdk1.7.0_51
6  打开C:\apache-tomcat-8.0.32-windows-x64\bin\startup.bat
7  在浏览器上输入网址 localhost:8080 (如果将Connector port="8080"改成了Connector port="9090" 则输入网址localhost:8080) 或 本地IP:8080 如能访问tomcat网页则正确配置了。
