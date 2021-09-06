# APIs

## API Design Best Practices

- What does REST stand for?

  - Representational State Transfer.

- REST APIs are designed around a :.

  - resources, which are any kind of object, data, or service that can be accessed by the client.

- What is an identifier of a resource? Give an example.

  - It is a URI that uniquely identifies that resource. For example, the URI for a particular customer
    > `https://adventure-works.com/orders/1`.

- What are the most common HTTP verbs?

  - The most common operations are GET, POST, PUT, PATCH, and DELETE.

- What should the URIs be based on?

  - resource URIs should be based on nouns (the resource) and not verbs (the operations on the resource).

- Give an example of a good URI.

  - `https://adventure-works.com/orders // Good`

  - `https://adventure-works.com/create-order // Avoid`

- What does it mean to have a ‘chatty’ web API? Is this a good or a bad - thing?
  - web APIs that expose a large number of small resources. Such an API may require a client application to send multiple requests to find all of the data that it requires.
  - We should avoid.
- What status code does a successful `GET` request return?
  - HTTP status code 200 (OK).

- What status code does an unsuccessful `GET` request return?
  - HTTP status code 404 (Not Found).

- What status code does a successful `POST` request return?
  - HTTP status code 201 (Created).

- What status code does a successful `DELETE` request return?
  - HTTP status code 204 (No Content).

  [source](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)

**[Back to: Homepage](https://omarhumamah.github.io/reading-note/).**
