# Утилита запаковывает структуру базы данных в JSON

## Build jar
Use 
mvn -Dmaven.test.skip=true install

## Run
Use
java -jar parserDB-0.0.1.jar --spring.datasource.url=<url> --spring.datasource.username=<username> --spring.datasource.password=<password>
where should you change <url>, <username>, <password> to your params without triangular brackets
