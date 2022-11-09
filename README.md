# IntoToAPIsNotes
1) An API is stored in a Server to await remote use through a client
2) The Client is used to translate to API into more accessile state
3) The Client exchanges data with the Server through an API
4) Computer Protocol is a set of rules for how two computers communicate
5) Main computer protocol is HTTP (Hyper-Text Transfer Protocol)
6) HTTP works through Request-Response Cycle (client sends server a request, server sends client a response)
7) Things needed for a valid client request: URL, Method, List of Headers, Body
8) URL ( Uniform Resource Locator) is a unique address
9) Method: requests used commonly to GET, POST, PUT, DELETE resources <- common method requests
10) Headers are meta-information about request like a list of items or a time stamp on a request
11) Body is the request body/syntax that it sends to the server
12) A Client has full control over a body
13) HTTP responses contain status codes that are used to convey simple information
14) JSON (JavaScript Object Notation) is built around its Keys(object attributes) and Values(the value set to the key)
15) XML (Extensible Markup Language) uses nodes inplace of keys and requires a root node
16) Content-Type header is used to let a server or client know a body is formatted a certain way
17) Client can specify accepted formats with the Accept header
18) Authetication is used to tell a server you are who you say you are
19) Basic Authentication is similar to username/password credentials
20) The information is compressed into a single value that is passed to the Autherizaton header
21) With API Key Authentication a credentials value can be given specific permissions
22) OAuth2 steps: User tells Client to connect to Server
                  Client directs User to Server (usually routes through authentication before sending user back with a callbackURL)
                  User logs in to Server granting Client access (after receiving credentials)
                  Server send User back to Client (an autherization code is hidden in the response)
                  Client exchanges code + secret key for access
                  Client fetches data from Server
23) OAuth1 requires the client to request a request token between steps 1 and 2 (this token acts as a authorization code for OAuth2)
24) OAuth1 access tokens do not expire
25) OAuth1 requires requests to be digitally signed
26) Scope is permissions that dictate a client's access to user data
27) SOAP is an XML based API structured for requests and responses
28) REST is an API used to manipulate resources
29) Endpoints are a URL that leads to a Resource
30) Resource API term for a business noun (object)
31) Pagination is the process of splitting up results into manageable chunks
