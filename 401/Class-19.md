# Read 19

## AWS: Events

### AWS SQS vs SNS<sup>1</sup>

#### 1. What is the difference betweeen SQS and SNS?

* SQS - Simple Queue Service: distributed queueing service
* SNS - Simple Notification Service: distributed publish-subscribe service

#### 2. What are some use cases for both SNS and SQS?

When different subscribers are subscribed to different queues that all get their information from a single SNS

### AWS SNS and SQS<sup>2</sup>

#### 1. Describe how to use SQS and SNS in a “fanout” pattern.

Some event causes an SNS notification to be sent to multiple different queues that care about the content of the SNS notification.

#### 2. Explain how “push notifications” work, using SNS.

Since it does not work like a queue, where the user needs to poll the queue for new notifications, when a SNS event happens, by nature, it sends a notification to the end point

### SQS and SNS Basics<sup>3</sup>

#### 1. How might a large scale, distributed application make use of a Queue system like SQS?

Using a FIFO queue - using 'message groups', messages belonging to the same message group will be consumed in the same order, which allows for scalability

### Bookmarks

* [SNS JavaScript SDK](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/SNS.html)
* [SQS JavaScript SDK](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/SQS.html)
  
### Footnotes

<sup>1</sup>https://medium.com/awesome-cloud/aws-difference-between-sqs-and-sns-61a397bf76c5

<sup>2</sup>https://www.youtube.com/watch?v=mXk0MNjlO7A

<sup>3</sup>https://www.youtube.com/watch?v=UesxWuZMZqI

[Back](/reading-notes/401/401-TOC.html)
