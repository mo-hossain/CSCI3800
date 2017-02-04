Request Headers:

cache-control:"no-cache"
-The browser or postman is telling the server to get a fresh version of the cache.

Postman-Token:"63c72632-b65f-4896-888f-85c0de623875"
-Takes care of basic authentication.

User-Agent:"PostmanRuntime/3.0.9"
-This is the information about agent sending the request and used for statistics, tracking and possible violations caused.
  
Accept:"*/*"
-All media types are accepted.

Host:"www.googleapis.com"
-This is the host of the api you are getting the api from.

accept-encoding:"gzip, deflate"
-Accepts media types but restricts their content-codings.

Response Headers:

expires:"Fri, 03 Feb 2017 19:08:02 GMT"
-Tells the user the date and time of when the response is stale.

date:"Fri, 03 Feb 2017 19:08:02 GMT"
-The date and time from when the message originated.

cache-control:"private, max-age=0, must-revalidate, no-transform"
-Single user cache thats age is no bigger than 0 seconds. It must be revalidated every time you talk to the server and the headers cannot be changed.

etag:""vFp1TYDMppbWxVi0Wgw_upD83cI/maQ21mT7PpXo0urNomSNVBO0klM""
-The current value of the entity tag for the requested variant.

vary:
-The Vary field value indicates the set of request-header fields that determines whether a cache is permitted to use the response to reply to a subsequent request without revalidation.

0:"Origin"
-The Origin header identifies the security contexts that caused the user agent to initiate an HTTP request.

1:"X-Origin"
-The Origin header identifies the security contexts that caused the user agent to initiate an HTTP request.

content-type:"application/json; charset=UTF-8"
-This indicates the media type of the entity-body sent to the user.

x-content-type-options:"nosniff"
-The X-Content-Type-Options response HTTP header is a marker used by the server to indicate that the MIME types advertised in the Content-Type headers should not be changed and be followed.

x-frame-options:"SAMEORIGIN"
-The X-Frame-Options HTTP response header can be used to indicate whether or not a browser should be allowed to render a page in a <frame>, <iframe> or <object>.

x-xss-protection:"1; mode=block"
-The HTTP X-XSS-Protection response header is a feature of Internet Explorer, Chrome and Safari that stops pages from loading when they detect reflected cross-site scripting (XSS) attacks.

content-length:"4279"
-The size of the entity body.

server:"GSE"
-The Server response-header field contains information about the software used by the origin server to handle the request.

alt-svc:"quic=":443"; ma=2592000; v="35,34""
-Allows the availability of alternative services to the client.