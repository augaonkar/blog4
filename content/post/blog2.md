---
title: "Amazon Route 53"
description: "This is the description"
date: 2018-05-05T13:39:59-07:00
draft: false
---


> AWS's DNS service, called Route 53, is a reliable and cost effective service for managing your domain. It has a simple RESTful API for managing them in the command-line.
 
Amazon Route 53 is a highly available and scalable cloud [Domain Name System (DNS)](https://aws.amazon.com/route53/what-is-dns/) web service. It is designed to give developers and businesses an extremely reliable and cost effective way to route end users to Internet applications by translating names like www.example.com into the numeric IP addresses like 192.0.2.1 that computers use to connect to each other. Amazon Route 53 is fully compliant with IPv6 as well.

Amazon Route 53 effectively connects user requests to infrastructure running in AWS – such as Amazon EC2 instances, Elastic Load Balancing load balancers, or Amazon S3 buckets – and can also be used to route users to infrastructure outside of AWS. You can use Amazon Route 53 to configure DNS health checks to route traffic to healthy endpoints or to independently monitor the health of your application and its endpoints. Amazon Route 53 Traffic Flow makes it easy for you to manage traffic globally through a variety of routing types, including Latency Based Routing, Geo DNS, Geoproximity, and Weighted Round Robin—all of which can be combined with DNS Failover in order to enable a variety of low-latency, fault-tolerant architectures. Using Amazon Route 53 Traffic Flow’s simple visual editor, you can easily manage how your end-users are routed to your application’s endpoints—whether in a single AWS region or distributed around the globe. Amazon Route 53 also offers Domain Name Registration – you can purchase and manage domain names such as example.com and Amazon Route 53 will automatically configure DNS settings for your domains.

***
{{<youtube xfCKXuofY60>}}

***

#### Benefits: 
* **Fast**: Route 53 uses Anycast with 24+ DNS servers distributed across world. Queries to your domain name will be resolved by the nearest DNS server.
* **Reliable**: AWS guaranties 100% availability for Route 53. Read the SLA to know more about this.
* **Integration with other services**: It’s designed to work closely with other services like EC2, S3, Cloudfront, etc.
* **API Support**: Ability to manipulate DNS is an important feature in Route 53. You can automate DNS management along with instance provisioning.




###### Read More 
[Route 53 Docementation](https://aws.amazon.com/documentation/route53/)
