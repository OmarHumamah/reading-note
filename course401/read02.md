# Express

- What’s the difference between PUT and PATCH?

  - `PUT`: used to update the source completely.
  - `PATCH`: used to make partial update to the source.

- Provide links to 3 services or tools that allow you to “mock” an API for development like json-server

  - https://opencollective.com/nock
  - https://www.mock-server.com/
  - https://beeceptor.com/

- Compare and contrast Swagger and APIDoc.js

  - 1 Which HTTP status codes should be sent with each type of (un)successful API call?
    - Swagger / APIDoc.js
      - responses:
        - 200:
          - description: OK
        - 400:
      - description: Bad request. User ID must be an integer and bigger than 0.
        - 401:
          - description: Authorization information is missing or invalid.
        - 404:
          - description: A user with the specified ID was not found.

- Compare and contrast SOAP and ReST
  - SOAP is a protocol that uses XML to communicate with a web server.
  - ReST is a protocol that uses JSON to communicate with a web server.

- `Web Server`: it is a software created to send and and receive data, information or even application to the web page or the clint. 
- `Express`: it is a backend framework to node.js, it allows the the javascript language to deal with servers and backend stuff. 
- `Routing`: it is a method to use the router control plane to provide services to applications
- `WRRC`: Web Request Response Cycle, request info from client and send a specific data to it.


