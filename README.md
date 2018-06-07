# examen
Examen 
 docker run -e PBA=primero -p 8686:8080 -v /home/gustavo/Documents/curso-dgp/vertx-sample/:/codExamen kebblar/jdk18-utf8-debug-maven mvn -f codExamen package

 docker run -e PBA=primero -p 8686:8080 -v /home/gustavo/Documents/curso-dgp/vertx-sample/:/codExamen kebblar/jdk18-utf8-debug-maven java -jar codExamen/target/sample-1.0-SNAPSHOT-fat.jar 
