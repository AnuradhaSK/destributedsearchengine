Navigate to overlaynetwork directory  and issue

`mvn clean install`

Inside /destributedsearchengine/target/
destributed-search-engine-1.0-SNAPSHOT.jar  will be available after a successful build

Execute as master:

 `java -jar destributed-search-engine-1.0-SNAPSHOT.jar 1`
 
 Execute as a peer:
 
  `java -jardestributed-search-engine-1.0-SNAPSHOT.jar 2 <ip> <port> <username>`