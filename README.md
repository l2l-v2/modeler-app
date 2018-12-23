# modeler-app
borrow the modeler developed by Flowable Open Software
# How to use the modeler?
- **Step1** : The modeler works ahead of the start up of the [flowable-idm-app](https://github.com/i-qiqi/flowabe-idm-app/tree/master), 
We have offer the runnable jar of the idm app under the root directory. you just run the following cmd to start it up. you can log in the idm app with default
credentials `admin/test` and url <http://localhost:8080/flowable-idm/index.html#/login>  
```
java -jar flowable-idm.jar --spring.datasource.username=<your own username> --spring.datasource.password=<your own password>
```
- **Step1** :  run the following cmd to start up the modler app. 
```
mvn clean install -Pmysql -DskipTests spring-boot:run -Dspring.datasource.username=<your own username> -Dspring.datasource.password=<your own password>
```
