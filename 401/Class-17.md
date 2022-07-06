# Read 17

## AWS: S3 and Lambda

### AWS S3<sup>1</sup>

#### 1. What is Amazon S3?

Amazon Simple Storage Service - object storage service

#### 2. Name some use cases for Amazon S3.

* Data lakes
* cloud-native applications
* mobile apps
* low-cost data archiving

#### 3. Name some benefits of using Amazon S3.

* Control access to data
* optimize costs with storage classes
* replicate data to any region
* access from on-premises or VPC
* protect and secure data
* gain visibility into storage

### AWS Lambda Basics<sup>2</sup>

#### 1. What is AWS Lambda?

A serverless computing service provided by AWS

#### 2. Name some use cases for AWS Lambdas.

* Serving web pages
* processing streams of data
* calling APIs
* integrating with other AWS services

#### 3. Describe “serverless” to a non-technical friend.

When you store your photos and documents to the cloud, it doesn't mean it doesn't get physically stored anywhere, it means it gets stored somewhere else that you can access by internet so that your local storage doesn't get overloaded.

### CDN<sup>3</sup>

#### 1. What is a CDN?

Content Delivery Network - geographically distributed group of servers that work together to provide fast delivery of Internet content.

#### 2. How does a CDN work with relation to the website visitor?

When the website visitor makes a request, the CDN will check the cache of the closest server. If that server has the content, it will send it to the user rather than make the longer trip to the original server; but it will still check the original server to make sure the cache is up to date

#### 3. What are the benefits of employing a CDN?

* Speeds up delivery of content
* Adds protection from cyber attacks like Denial of Service attacks

### Footnotes

<sup>1</sup>https://aws.amazon.com/s3/

<sup>2</sup>https://www.serverless.com/aws-lambda

<sup>3</sup>https://cyberhoot.com/cybrary/content-delivery-network-cdn/

[Back](/reading-notes/401/401-TOC.html)