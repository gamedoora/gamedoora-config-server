# Gamedoora Configuration Service  
Gamedoora Configuration Service provides all the configuration for all the Gamedoora services. 
The service is backed by properties files in the `configs` directory of the user's home directory.  

## Requirements
- JDK 17
- Maven 3.3 or higher

## Build
```
./mvnw clean install
```
## Steps for adding confiiguration for a service  
1. Create directory named `configs` in your home directory.  
2. Add service specific properties files in the `configs` directory with names as per the convention in the conventions section.  
3. The properties files should have properties defined as follows:
   <service_name>.prop1=value1  
A sample properties file can be found in the sample directory.
  

## Properties file naming convention
- <service_name>.properties
- <service_name>.<profile>.properties
