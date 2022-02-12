# FibonacciRestApi
HttpRequest via Apex
1. Created in my org of Salesforce TestObject that contains 3 Fibonacci sequences
2. In the Developer Console is created a class FibonacciRestApi, which receives these sequences via HttpRequest and deserialize them from the JSON format
3. Method ReverseOrder() reverses the order of numbers in lists;
4. The class ClassDataLoader() extracts a list of lists from the FibonacciReverseOrder__c object and inserts them into a file - fbn2.csv
5. Logging was made at all stages of the development by statements of the System.debug, as well as the Log Inspector.
6. FibonacciRestApiTest class covers our code with tests
7. Added static resource for HTTPCalloutMock interface - GetRestApiResource.txt
