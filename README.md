# springBatchDemo
Spring batch demo project that read data from csv file and write to H2 in memory DB
---
update input key's value in application.properties file wrt your machine path.
example: input=file:C:/Users/Kumar/git/springBatchDemo/src/main/resources/users.csv
---
Login H2 from console:
---
localhost:8182/h2-console/
---
update JDBC URL: jdbc:h2:mem:testdb
---
now connect, all tables will be visibles.
---
insert data using the url: http://localhost:8182/load
---

