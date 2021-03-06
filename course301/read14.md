# Authentication

## What is OAuth

- What is OAuth?
  - OAuth is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential. In authentication parlance, this is known as secure, third-party, user-agent, delegated authorization.

- Give an example of what using OAuth would look like.
  - The simplest example of OAuth is when you go to log onto a website and it offers one or more opportunities to log on using another website’s/service’s logon.

- How does OAuth work? What are the steps that it takes to authenticate the user? 
  01. The first website connects to the second website on behalf of the user, using OAuth, providing the user’s verified identity. 
  02. The second site generates a one-time token and a one-time secret unique to the transaction and parties involved. 
  03. The first site gives this token and secret to the initiating user’s client software. 
  04. The client’s software presents the request token and secret to their authorization provider (which may or may not be the second site). 
  05. If not already authenticated to the authorization provider, the client may be asked to authenticate. After authentication, the client is asked to approve the authorization transaction to the second website. 
  06. The user approves (or their software silently approves) a particular transaction type at the first website. 
  07. The user is given an approved access token (notice it’s no longer a request token). 
  08. The user gives the approved access token to the first website. 
  09. The first website gives the access token to the second website as proof of authentication on behalf of the user. 
  10. The second website lets the first website access their site on behalf of the user. 
  11. The user sees a successfully completed transaction occurring. 
  12. OAuth is not the first authentication/authorization system to work this way on behalf of the end-user. In fact, many authentication systems, notably Kerberos, work similarly. What is special about OAuth is its ability to work across the web and its wide adoption. It succeeded with adoption rates where previous attempts failed (for various reasons).

- What is OpenID?
  - OpenID is about authentication
  - OpenID is for humans logging into machines

[source](https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html)

## Authorization and Authentication flows

- What is the difference between authorization and authentication?
  - In simple terms, authentication is the process of verifying who a user is, while authorization is the process of verifying what they have access to.
- What is Authorization Code Flow?
  - ![auth](auth-sequence-auth-code.png)

## Things I want to know more about

- What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
- What is Implicit Flow with Form Post?
- What is Client Credentials Flow?
- What is Device Authorization Flow?
- What is Resource Owner Password Flow?

[source](https://auth0.com/docs/authorization/flows)

**[Back to: Homepage](https://omarhumamah.github.io/reading-note/).**
