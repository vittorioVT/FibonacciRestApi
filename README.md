# FibonacciRestApi
HttpRequest via Apex
1. Data is posted on an external resource in json format - https://scoutoutfit.com/fibonacci3.json
2. In the Developer Console of org is created a class FibonacciRestApi, which receives these sequences via HttpRequest and deserialize them from the JSON format
3. Method ReverseOrder() reverses the order of numbers in lists;
4. The class ClassDataLoader extracts a list of lists from the FibonacciReverseOrder__c object and inserts them into a file - fbn2.csv
5. Logging was made at all stages of the development by statements of the System.debug, as well as the Log Inspector.
6. FibonacciRestApi class is covered tests FibonacciRestApiTest class
7. GetRestApiResource.txt is static resource for HTTPCalloutMock interface. 
8. ClassDataLoader class is covered tests ClassDataLoaderTest class.
