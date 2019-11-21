# jBase
Sample code for proccessing and responding with JSON on jBase using jAgent.
'request.json' would be sent to the jAgent server running on jBase.
jAgent would send the request to 'RESTFUL' via a listener. 'RESTFUL' would convert the JSON to and object, check permissions, and determine what subroutine to call.
In this example, it would call 'JSON.WEB.REPORT'. 'JSON.WEB.REPORT' would generate the object to be returned.
'RESTFUL' would convert the object back to JSON, and return it back up the chain.
'response.json' is the example of the JSON that would be returned to the client.
