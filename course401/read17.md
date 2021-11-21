# AWS: S3 and Lambda

## Describe “The Cloud”
- The Cloud is a generic term for remotely accessed storage. This storage is accessed through the internet. Users do not actually know where their data is stored - the geographical location is unimportant. Users only need to know that their data is stored on a server connected to the internet.
## What is a container (as it relates to computers and servers)?
-  Containers are a form of operating system virtualization. A single container might be used to run anything from a small microservice or software process to a larger application. Inside a container are all the necessary executables, binary code, libraries, and configuration files.
## What is auto-scaling?
- It is the process of monitoring your applications and automatically adjusting capacity to maintain steady, predictable performance at the lowest possible cost. 
- It is a cloud computing technique for dynamically allocating computational resources. Depending on the load to a server farm or pool, the number of servers that are active will typically vary automatically as user needs fluctuate.
- Auto scaling and load balancing are related because an application typically scales based on load balancing serving capacity.
## What is bandwidth?
- The maximum amount of data transmitted over an internet connection in a given amount of time. Bandwidth is often mistaken for internet speed when it's actually the volume of information that can be sent over a connection in a measured amount of time – calculated in megabits per second (Mbps).
## How do cloud providers compute service costs?
- When setting price, cloud providers determine the expense to maintaining the network. They start by calculating costs for network hardware, network infrastructure maintenance, and labor. These expenses are added together and then divided by the number of rack units a business will need for its IaaS cloud. 

---

- `Server Instances`:It is a server running our application. Think of one server as one instance. An Instance is a virtual machine which runs our workloads in the cloud. Often the term VM Virtual Machine & Instance are used interchangeably. The term server & instance can also be used interchangeably but in the cloud computing universe, the term instance is always preferred over the server.
- `Cloud Services`: It  is the on-demand availability of computer system resources, especially data storage and computing power, without direct active management by the user. Large clouds often have functions distributed over multiple locations, each location being a data center
- `Cloud Architecture`: It refers to the components and sub-components required for cloud computing. These components typically consist of a front end platform, back end platforms, a cloud based delivery, and a network.
- `EC2/Beanstalk vs Heroku`:
    - The first observation is that these solutions are roughly comparable with the same cost; $250 (Heroku) v.s. $222 (AWS Elastic Beanstalk) per month.
    - The next observation is that the AWS Elastic Beanstalk solution’s PostgreSQL Instances, being in private Subnets with restricted Security Groups, are more secure than the publicly available PostgreSQL Instances in the Heroku solution.
    - Heroku’s Private Spaces feature can be used to address this issue; the problem though is that this feature is only available with custom pricing (assuming going to be expensive).
    - Another observation is that Heroku’s Dyno high availability, by randomly distributing across Availability Zones, is less robust than the AWS Elastic Beanstalk’s (actually powered by an EC2 Auto Scaling Group) active distribution across Availability Zones.

    [source](https://codeburst.io/heroku-v-s-aws-elastic-beanstalk-1cc6f12ca3c7)

---

## What is AWS Lambda?
- AWS Lambda is a serverless computing service provided by Amazon Web Services (AWS). Users of AWS Lambda create functions, self-contained applications written in one of the supported languages and runtimes, and upload them to AWS Lambda, which executes those functions in an efficient and flexible manner.

- The Lambda functions can perform any kind of computing task, from serving web pages and processing streams of data to calling APIs and integrating with other AWS services.

- The concept of “serverless” computing refers to not needing to maintain your own servers to run these functions. AWS Lambda is a fully managed service that takes care of all the infrastructure for you. And so “serverless” doesn’t mean that there are no servers involved: it just means that the servers, the operating systems, the network layer and the rest of the infrastructure have already been taken care of, so that you can focus on writing application code.

[source](https://www.serverless.com/aws-lambda)

## Amazon S3
- It is Object storage built to retrieve any amount of data from anywhere

    ### How it works
    - Amazon Simple Storage Service (Amazon S3) is an object storage service offering industry-leading scalability, data availability, security, and performance. Customers of all sizes and industries can store and protect any amount of data for virtually any use case, such as data lakes, cloud-native applications, and mobile apps. With cost-effective storage classes and easy-to-use management features, you can optimize costs, organize data, and configure fine-tuned access controls to meet specific business, organizational, and compliance requirements.

[source](https://aws.amazon.com/s3/)