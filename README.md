# jBase
Sample code for proccessing and responding with JSON on jBase using jAgent.
1. **request.json** would be sent to the jAgent server running on jBase.
2. jAgent would send the request to **RESTFUL** via a listener. **RESTFUL** would convert the JSON to and object, check permissions, and determine what subroutine to call.
3. In this example, it would call **JSON.WEB.REPORT**, which would generate the object to be returned.
4. **RESTFUL** would convert the object back to JSON, and return it back up the chain.
5. **response.json** is the example of the JSON that would be returned to the client.
