#  Bearer Authorization

## Write the following steps in the correct order:
- Ask the client if they want to sign in via a third party
- Make a request to a third-party API endpoint
- Redirect to a third party authentication endpoint
- Register your application to get a client_id and client_secret
- Receive authorization code
- Receive access token
- Make a request to the access token endpoint
## What can you do with an authorization code?
- it can be used to generate access token for the JWT, it contain the password and the user name for the user access. The username is used by the token to decode an access token. 
## What can you do with an access token?
- The access token is generated to make an authorized access to a website without hitting the username and password every time you enter the web site. you make a sign in once the the token will be generated and saved on local storage then it will be your key to enter automatically every time you enter the website.
## What’s a benefit of using OAuth instead of your own basic authentication?
- to give the user authenticated access from third party trusted sites. when the user is authenticated im third party site which is completely secure the web will conceder that the user is authenticated and take the id and user name from the third party and git access throw it.  

---

- `Client ID`: It is a public identifier for apps or api. it must be unique for every app. also usually it consists from 32-characters so it will not be guessable by the third party   
- `Client Secret`: It is like a stamp for the apps or api. it should be unique and secret. it is a secret known only to your application and the authorization server. It protects your resources by only granting tokens to authorized requestors. Protect your client secrets and never include them in mobile or browser-based apps.
- `Authentication Endpoint`:
- `Access Token Endpoint`:
- `API Endpoint`: It is the point which the app can communicate with the client; pass data and information or do (CRUD) methods.
- `Authorization Code`: It is alphanumerical pass-code for user to be authorized.
- `Access Token`: an access or a key given to the user to be allowed to enter the site without typing his/her password and username over and over, based on specific authorization.   