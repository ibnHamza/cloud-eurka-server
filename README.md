Eureka Server for service discovery, ready to run on local

download the ZIP file <demo-cloud-eurka> and import as maven project on your IDE

1- build the project using 
  mvn clean package
2- run the app 
  open CMD
  go to target folder inside the project folder, run below command
  java -jar <app-name>.jar 
3- test the app by open the browser, type 
  http://localhost:9998
  you should get Eureka default page, now on your apps you should include Eureka client and configure to use http://localhost:9998
