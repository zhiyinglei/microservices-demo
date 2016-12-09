###In target folder, you can run it locally  :

target/microservice-demo-1.1.0.RELEASE.jar is  defaultZone: http://localhost:1111/eureka/


1. In the first window run: java -jar target/microservice-demo-1.1.0.RELEASE.jar registration and wait for it to start up

2. Switch to the second window and run: java -jar target/microservice-demo-1.1.0.RELEASE.jar accounts and again wait for it to start up

3. In the third window run: java -jar target/microservice-demo-1.1.0.RELEASE.jar web

4. In your favorite browser open the same two links: http://localhost:1111 and http://localhost:3333



###In reg and accounts folder ,

 app.jar is  defaultZone: http://reg:1111/eureka/
 
run following command in root 

docker-compose up --build -d 
