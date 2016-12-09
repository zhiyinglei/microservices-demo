###In target folder, you can run it locally  :

In each window, change to the directory where you cloned the demo

In the first window, build the application using mvn clean package

In the same window run: java -jar target/microservice-demo-1.1.0.RELEASE.jar registration and wait for it to start up

Switch to the second window and run: java -jar target/microservice-demo-1.1.0.RELEASE.jar accounts and again wait for it to start up

In the third window run: java -jar target/microservice-demo-1.1.0.RELEASE.jar web

In your favorite browser open the same two links: http://localhost:1111 and http://localhost:3333



