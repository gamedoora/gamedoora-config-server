# Gamedoora Configuration Service  
Gamedoora Configuration Service provides all the configuration for all the Gamedoora services. 
The service is backed by properties files in a location specified as value of CONFIG_LOCATIONS environment variable.

## Requirements
- JDK 1.8 or higher
- Maven 3.3 or higher

## Build
```
mvnw clean install
```  

## Properties file naming convention
- gamedoora.properties.dev
- gamedoora.properties.qa
- gamedoora.properties.prod
