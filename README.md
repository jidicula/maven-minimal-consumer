# maven-minimal-consumer


1. `mvn dependency:purge-local-repository -DactTransitively=false -DreResolve=false -Dverbose=true`
2. `mvn clean install`
1. `mvn exec:java -D exec.mainClass=com.mycompany.app.App --no-transfer-progress`
