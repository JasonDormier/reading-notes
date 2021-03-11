---
layout: post
title: "AWS: S3 and Lambda"
permalink: /class-16
---
Jason D


##### What’s the difference between a FIFO and a standard queue?
* FIFO is first in first out, where as standard queues support "exactly one" processing and ordering of the queue

##### How can the server be assured a message was properly received?
* The client can emit right back to the server that the message was received

##### What classic design pattern is best represented by event driven programming?
* The observer pattern is a software design pattern in which an object, named the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods

##### How do you test an event driven system?
* Unit tests, which will test individual parts of the system

### Vocabulary Terms

##### Server Instances
* General purpose - instances provide a balance of compute, memory and networking resources, and can be used for a variety of diverse workloads. These instances are ideal for applications that use these resources in equal proportions such as web servers and code repositories. 

* Compute Optimized -  instances are ideal for compute bound applications that benefit from high performance processors. Instances belonging to this family are well suited for batch processing workloads, media transcoding, high performance web servers, high performance computing (HPC), scientific modeling, dedicated gaming servers and ad server engines, machine learning inference and other compute intensive applications.

* Memory optimized -  instances are designed to deliver fast performance for workloads that process large data sets in memory.

* Accelerated computing -  instances use hardware accelerators, or co-processors, to perform functions, such as floating point number calculations, graphics processing, or data pattern matching, more efficiently than is possible in software running on CPUs.

* Storage optimized - instances are designed for workloads that require high, sequential read and write access to very large data sets on local storage. They are optimized to deliver tens of thousands of low-latency, random I/O operations per second (IOPS) to applications.

https://aws.amazon.com/ec2/instance-types/

##### Containers
* provide a standard way to package your application’s code, configurations, and dependencies into a single object. Containers share an operating system installed on the server and run as resource-isolated processes, ensuring quick, reliable, and consistent deployments, regardless of environment
https://aws.amazon.com/getting-started/deep-dive-containers/

##### Cloud Services
* Cloud based storage and other useful tools and entertainment features

##### Cloud Architecture
*  refers to the components and subcomponents required for cloud computing. These components typically consist of a front end platform (fat client, thin client, mobile ),back end platforms (servers, storage), a cloud based delivery, and a network (Internet, Intranet, Intercloud). Combined, these components make up cloud computing architecture.
https://en.wikipedia.org/wiki/Cloud_computing_architecture

##### AWS
* Amazon Web Services

##### EC2/Beanstalk vs Heroku
* Preform roughly the exact same task of being able to perform hosting for backend development
