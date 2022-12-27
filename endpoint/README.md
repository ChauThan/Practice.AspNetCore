# Shows how to retrieve and inspect the endpoint matching the current request
The endpoint, if selected, can be retrieved from the HttpContext. 
Its properties can be inspected. 
Endpoint objects are immutable and cannot be modified after creation. 
The most common type of endpoint is a RouteEndpoint. 
RouteEndpoint includes information that allows it to be selected by the routing system.