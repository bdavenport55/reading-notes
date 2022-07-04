# Read 16

## AWS: Cloud Servers

### AWS EC2<sup>1</sup>

#### 1. What is an EC2 Instance?

A virtual server

#### 2. Name 2 use cases for EC2.

* Running cloud-native and enterprise applications
* Developing Apple platforms

#### 3. Provide 1 reason to use ECS instead of Heroku.

ECS supports automatic scaling of apps

### EC2 for Humans<sup>2</sup>

#### 1. Where can we find EC2 on the AWS Console?

Under the compute section

#### 2. Explain the general difference between T2 Micro and XL.

* T2 Micro: 1vCPU, 1 GiB RAM, 1:1
* T2 XL: 4 vCPU, 16 GiB RAM, 1:4

#### 3. Explain a “Compute Cycle” to a non-technical friend.

In the same way you need to restart your computer so that updates can be applied, the virtual server needs to periodically be stopped and started again.

### Elastic Beanstalk<sup>3</sup>

#### 1. What is Elastic Beanstalk?

A service that deploys, manages, and scales web apps/services for devs.

#### 2. Describe the relationship between EC2 and Elastic Beanstalk.

EC2 is a service that Beanstalk uses.

#### 3. Name some benefits of using Elastic Beanstalk.

* Beanstalk autmatically handles load balancing, provisioning, auto scaling, and monitoring of app health
* Retain full control over AWS resources controlling the app
* Reduces need to manage architecture, so you can focus solely on content
* No extra cost on top of AWS services you already pay for

### Bookmarks

[Virtual Machines](https://www.youtube.com/watch?v=yIVXjl4SwVo)

[VMS and the Cloud](https://www.youtube.com/watch?v=l0DfHUWMjsU)

### Footnotes

<sup>1</sup>https://aws.amazon.com/ec2/

<sup>2</sup>https://www.youtube.com/watch?v=lZMkgOMYYIg

<sup>3</sup>https://www.youtube.com/watch?v=SrwxAScdyT0

[Back](/reading-notes/401/401-TOC.html)