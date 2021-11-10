# Authorization/Authentication

## What header(s) are used in authentication and authorization
- In `basic` HTTP authentication, a request contains a header field in the form of Authorization: Basic <credentials> , where credentials is the Base64 encoding of ID and password joined by a single colon : . It is specified in RFC 7617 from 2015, which obsoletes RFC 2617 from 1999.
- In `bearer`-**token**- authentication the client must send this token in the Authorization header when making requests to protected resources: Authorization: Bearer token
## What is safe to put into a JWT
-  You should use API secret,a strong one. The general opinion is that they're good for being used as ID Tokens or Access Tokens and that they're secure - as the tokens are usually signed or even encrypted.  
## How are JWTs validated
- JWT is created with a secret key and that secret key is private to you which means you will never reveal that to the public or inject inside the JWT token. When you receive a JWT from the client, you can verify that JWT with this that secret key stored on the server.

- `RBAC`: It is a method of restricting network access based on the roles of individual users within an enterprise. RBAC ensures employees access only information they need to do their jobs and prevents them from accessing information that doesn't pertain to them.
- `User Roles`: User Roles are permission sets that control access to areas and features within the Professional Archive Platform. Each User account requires a Role assignment.
- `JWT Token`: It is a proposed Internet standard for creating data with optional signature and/or optional encryption whose payload holds JSON that asserts some number of claims. The tokens are signed either using a private secret or a public/private key.

