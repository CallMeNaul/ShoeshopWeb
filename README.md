# Shoe-Shopping-Cart
Shoe Shopping Cart built with SpringBoot, JPA, MySQL , Spring Security, Hibernate and Thymeleaf

![image](https://user-images.githubusercontent.com/29988949/75882730-9ad11680-5dd6-11ea-9648-252426582a96.png)


![image](https://user-images.githubusercontent.com/29988949/75947593-c6dfac80-5e55-11ea-8582-bce667beb9bb.png)

`ProductList Page`

![image](https://user-images.githubusercontent.com/29988949/75968115-bf35fd00-5e81-11ea-9bae-e78ff047dcfd.png)

`Cart Page`

![image](https://user-images.githubusercontent.com/29988949/75956013-da960d80-5e6b-11ea-84b2-a0ca854ef9c9.png)
## Deployment
### 1. Move to src/main/resources/application.properties
Edit address server, port, database name, username and password
```sh
spring.datasource.url=jdbc:mysql://<address_server>:<port>/<database_name>
spring.datasource.username=<username>
spring.datasource.password=<password>
```
For example with Jar file I built:
```sh
spring.datasource.url=jdbc:mysql://172.18.0.2:3306/shoeshop
spring.datasource.username=root
spring.datasource.password=shoeshop
```
### 2. Build Jar File
```sh
mvn install DskipTests=true
```
You will see the "target" directory after building.
### 3. Build image and run docker compose
