# Sample example on WireMock standalone
Mocking REST API using WireMock standalone 

# How to run this application
1. Go to the checkout directory
2. Run command java -jar wiremock-standalone-2.18.0.jar --verbose
To see more options http://wiremock.org/docs/running-standalone/

3. Verify mock API http://localhost:8080/api/mytest

# How to mock new API
Create json file and put under mappings folder. Similar to mytest json file. Refer http://wiremock.org/docs/request-matching/ for complex request matching 
