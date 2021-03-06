# CRUD

## Status Codes Based On REST Methods

- In your own words, describe what each group of status code represents:

  - 100’s = they usually tell the client that the header part of the request has been received and the server will try to comply with a transmission demand of the client.
  - 200’s = They tell the client that its request was accepted. In case of asynchronous processing of a request (202), this doesn’t mean the request was successfully processed only that it met all validation requirements at the time of sending.
  - 300’s = They tell the client that the resource they are requesting isn’t available at the expected location anymore. This can have multiple reasons, be temporary or permanent, but the client has to issue a request to the new location.
  - 400’s = They are all about invalid requests a client sent to a server. There are several causes to this, timeouts, wrong URI, missing authentication, etc.
  - 500’s = they indicate problems with overwhelmed servers or unreachable servers behind proxies, but sometimes they can be directly related to client requests that trigger error exceptions on the server.

- What is a status code 202?
  - This code tells the client that the request was valid, but its processing will finish sometime in the future. The response body should include an URL to the finished resource with some information about when it will be available, or an URL to some monitoring endpoint that tells the client when the resource is available.
- What is a status code 308?

  - This is the right code if the resource will now be available at a new URL and the client should directly access it via the new URL in the future. The current endpoint can’t control the clients’ behavior after the request and a subsequent redirect if the resource URL changes again have to be issued from the new URL.

- What code would you use if an update didn’t return data to a client?
  - `204 No Content`

- What code would you use if a resource used to exist but no longer does?
  - `410 Gone`

- What is the ‘Forbidden’ status code?
  - `403 Forbidden` - The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.

[source](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

## IMPORTANT VIDEO

[![IMAGE_ALT](https://img.youtube.com/vi/UCFbNIlppjAuEX4znoulh0Cw/0.jpg/default.jpg)](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw)

**[Back to: Homepage](https://omarhumamah.github.io/reading-note/).**
