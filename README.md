# Maven Quickstart Archetype, Adding JAR Archive Config

## Creation

### Archetype
`mvn archetype:generate -DarchetypeGroupId=org.apache.maven.archetypes -DarchetypeArtifactId=maven-archetype-quickstart -DarchetypeVersion=1.4`

### Jar packaging
Added `maven-jar-plugin`config

## Test
`mvn test`

## Build
`mvn clean package`

## Run

### Before jar config
`java -cp target/basic-archetype-test-1.0-SNAPSHOT.jar org.example.App`

### After jar config
`java -jar target/basic-archetype-test-1.0-SNAPSHOT.jar`
