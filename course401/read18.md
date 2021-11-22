# AWS: API, Dynamo and Lambda

## What are serverless functions?

- It is anonymous function that do not need ant server to respond. A serverless function is a programmatic function written by a software developer for a single purpose. It's then hosted and maintained on infrastructure by cloud computing companies. These companies take care of code maintenance and execution so that developers can deploy new code faster and easier.

## If you were to create a system that emulated Lambda functions, how would you do it?

- [emulate lambda function](https://www.fugue.co/blog/2015-10-29-aws-lambda-emulator.html)

## Describe how a CDN works

- A content delivery network. It is a network of servers that distributes content from an “origin” server throughout the world by caching content close to where each end user is accessing the internet via a web-enabled device. The content they request is first stored on the origin server and is then replicated and stored elsewhere as needed. By caching content physically close to where a user is and reducing the distance it has to travel, latency is reduced. This process also decreases stress on origin servers by distributing the load geographically across multiple servers.
- [source](https://www.akamai.com/our-thinking/cdn/what-is-a-cdn)

---

- `Serverless Functions`: It is a programmatic function written by a software developer for a single purpose.

- `Cloud Storage`: It s a cloud computing model that stores data on the Internet through a cloud computing provider who manages and operates data storage as a service.

- `CDN`: A content delivery network (CDN) refers to a geographically distributed group of servers that work together to provide fast delivery of Internet content.

---

## Amazon API Gateway

- In this guide, we’ll walk you through all the details of API Gateway. We’ll show you how it can be used with the Serverless Framework and give you a list of resources should you want to learn even more.

- Recently, AWS also launched AWS HTTP APIs. These are a potential alternative to API Gateway REST APIs that we discuss in detail in our Ultimate Guide to AWS HTTP APIs.

- Amazon API Gateway is a managed service that allows developers to define the HTTP endpoints of a REST API or a WebSocket API and connect those endpoints with the corresponding backend business logic. It also handles authentication, access control, monitoring, and tracing of API requests.

- Many Serverless applications use Amazon API Gateway, which conveniently replaces the API servers with a managed serverless solution.

[source](https://www.serverless.com/guides/amazon-api-gateway)

## Amazon DynamoDB
- Fast, flexible NoSQL database service for single-digit millisecond performance at any scale 
- How it works
    - Amazon DynamoDB is a fully managed, serverless, key-value NoSQL database designed to run high-performance applications at any scale. DynamoDB offers built-in security, continuous backups, automated multi-region replication, in-memory caching, and data export tools.

[source](https://aws.amazon.com/dynamodb/)

## Dynamoose

- Dynamoose is a modeling tool for Amazon's DynamoDB. Dynamoose is heavily inspired by Mongoose, which means if you are coming from Mongoose the syntax will be very familar.

- Key Features
    - Type safety
    - High level API
    - Easy to use syntax
    - Ability to transform data before saving or retrieving documents
    - Strict data modeling (validation, required attributes, and more)
    - Support for DynamoDB Transactions
    - Powerful Conditional/Filtering Support
    - Callback & Promise support