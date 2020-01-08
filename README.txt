This is a very simple example of how to retrieve data using Blackbaud Grantmaking API.
An API Key needs to be purchased before endpoints can be hit.
There are two values inside the API Key text file you will receive after the purchase.
The first value is the userID and the second one is the privateKey.
First a Bearer token needs to be retrieved and then 
"bearer " + token
is going to be the token needed to pass as a header into the next ajax call to retrieve data (a request in this app).