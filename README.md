# JMeter


mysql & docker & Jmeter

https://severalnines.com/blog/mysql-docker-containers-understanding-basics

docker run --detach --name=test-mysql --env="MYSQL_ROOT_PASSWORD=mypassword" -p 3308:3306 mysql



we need to place this jar file under lib folder mysql-connector-java-8.0.16.jar
in JDBC connection configuration -> give pool name as per your wish and use the same pool name JDBC reuest
jdbc:mysql://localhost:3308/mysql -> here mysql is database and give "use movies" under Init SQL statement separated by new line


 com.mysql.jdbc.Driver
 root
 mypassword
