Navigate to overlaynetwork directory  and issue

`mvn clean install`

Inside /destributedsearchengine/target/
distributed-search-engine-1.0-SNAPSHOT.jar  will be available after a successful build

Execute as master:

 `java -jar distributed-search-engine-1.0-SNAPSHOT.jar 1`
 
 Execute as a peer:
 
  `java -jar distributed-search-engine-1.0-SNAPSHOT.jar 2 <ip> <port> <username>`
