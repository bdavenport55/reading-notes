# Read 18

## AWS: API, Dynamo and Lambda

### AWS API Gateway Overview<sup>1</sup>

#### 1. What is Amazon API Gateway?

A managed service that allows developers to define HTTP endpoints of a REST API or a WebSocket API and connect those endpoints with the corresponding backend business logic - essentially a service for building serverless APIs

#### 2. Why is Amazon API Gateway an important part of the Serverless ecosystem?

It integrates with other AWS services - Lambda, SNS, IAM, and Cognito Identity Pools - which allows for management of auth and metrics and tracing for API requests.

#### 3. How does API Gateway integrate with other AWS services?

It allows for management of auth, and metrics and tracing for API requests.

### AWS API Gateway<sup>2</sup>

#### 1. What are the some benefits of using Amazon API Gateway?

* Efficient API development
* Performance at any scale
* Cost savings at scale
* Easy monitoring
* Flexible security controls
* RESTful API options

#### 2. What two API types might you choose from?

* RESTful APIs
* WebSocket APIs

### AWS DynamoDB Guide<sup>3</sup>

#### 1. What is DynamoDB?

A hosted NoSQL database offered by AWS

#### 2. Under what circumstances would you recommend DynamoDB over MongoDB?

* Apps with large amounts of data and strict latency requirements
* Serverless applications using AWS Lambda
* Data sets with simple, known access patterns

### AWS DynamoDB<sup>4</sup>

#### 1. Explain to a non-technical friend how DynamoDB works.

If you're using an app that you can add a lot of items to, the memory it takes up would start getting to be a lot, so instead of saving it on your phone, the app stores it to the cloud. Then, when the app needs information again, it can just reach out to the cloud and return it to you.

### Dynamoose<sup>5</sup>

#### 1. What is Dynamoose?

A modeling tool for Amazon's DynamoDB - is heavily inspired by Mongoose

#### 2. What are some key features of Dynamoose?

* Type safety
* High level API
* Easy to use syntax
* Ability to transform data before saving or retrieving documents
* Strict data modeling (validation, required attributes, and more)
* Support for DynamoDb Transactions
* Powerful Conditional/Filtering Support
* Callback & Promise support

### Footnotes

<sup>1</sup>https://www.serverless.com/guides/amazon-api-gateway

<sup>2</sup>https://aws.amazon.com/api-gateway/

<sup>3</sup>https://www.dynamodbguide.com/what-is-dynamo-db/

<sup>4</sup>https://aws.amazon.com/dynamodb/

<sup>5</sup>https://dynamoosejs.com/getting_started/Introduction/

[Back](/reading-notes/401/401-TOC.html)