---
layout: post
date: 2016-05-16
author: Alex
authorlink: https://twitter.com/anuttgens
title: Cloud Services Plaforms
excerpt: Amazon Web Services, and how it helped me make [Good HQ](https://goodhq.org)
tags: useful digital tools
image:
---

About a year back, I started working on the [Good HQ](https://goodhq.org) project, [SCVO](http://www.scvo.org.uk/)'s new charity social media site. This is no small task, and as an experimental project, it uses a number of pretty new technologies. As it doesn't rely on the [SCVO](http://www.scvo.org.uk/)'s existing infrastructure, it needs its own database, its own servers, testing sites, web addresses, and basically everything a stand-alone platform requires, so there's the question of how to achieve all this? For most of the time I've been the only developer on this project, for the last couple of months I've been ably assisted by Calum on the design and appearance of the site, but it would be a lot of work for one developer to set all of this up, it'd also cost a lot in terms of servers. This is where cloud services platforms like [AWS](https://http://aws.amazon.com/) and [Azure](https://azure.microsoft.com/) come in. 

## Why AWS?

Part of the initial mandate of this project was that we would try to think of the project as a start-up company would, and so the technologies chosen weren't based on the current SCVO systems, but web research. Both Amazon’s AWS and Microsoft’s Azure platforms are commonly used for projects of this type. Azure is a popular choice for larger companies, but as Amazon's AWS service is commonly used for start-ups, we made the decision to go with that.

## The Old Way

In the old days, if you wanted to set up a web platform like GoodHQ, one of the things you'd need would be a Systems Administrator, a person whose job it would be to get hold of the servers, take the code written by the developer (me) and get it up and running on these servers, and keep a check of them to make sure they're running correctly. If the business did well, we'd have to decide between getting a bigger server, or trying to run the application on multiple servers.

## The New Way

Cloud services like Amazon AWS, do away with the need for a [Systems Administrator](https://en.wikipedia.org/wiki/System_administrator) for small projects like ours, and makes the job of a SysAdmin easier for more developed projects. To achieve this aim, it provides a mulitude of linked services which make setting up a platform like [Good HQ](https://goodhq.org) much easier, by taking the work away from me. For this project alone we've used the following AWS services:

### S3 

[S3](https://aws.amazon.com/s3/) this is like an online hard-drive, it means that I've got a secure place to store user profile images, videos or other large files which I don't need to worry about back-ups for. Without S3 I'd need to make sure I had a server, and check that it had the space to handle all of this information. I'd also need to provide a second place, to make sure this information was backed up.

### Elastic Beanstalk

[Elastic Beanstalk](https://aws.amazon.com/elasticbeanstalk/) allows for simple deployment. This means that rather than having to take care of multiple servers, and write complex automation code to get my the application online, I can use simple commands to upload the code (a little setup, then just typing "eb deploy"), and then it'll be sent to the AWS servers. Without Elastic Beanstalk I'd have to make sure I'd created my own servers, check they were working, and if traffic got heavy, buy another server, and then find a way to direct the traffic between the old server and the new. Elastic Beanstalk saves me a great deal of time, money and effort.

### Route 53

[Route 53](https://aws.amazon.com/route53/) helps me with DNS, which lets users get to [Good HQ](https://goodhq.org), and helps with the situation where Elastic Beanstalk has made multiple servers for the [Good HQ](https://goodhq.org) platform.

### SES 

[SES](https://aws.amazon.com/ses/) means I don't have to worry about setting up my own email server, once again saves effort and money.

### GrapheneDB

[GrapheneDB](http://www.graphenedb.com/) is a third party service, which exists both on AWS and Azure. It provides us with a [Neo4J](http://neo4j.com/) database, and does the maintenance (backups, restarts, configuration for us). Without Graphene, I'd have to set up and maintain our database on one of our servers.


## The Result

These services together, constitute some of the many technologies which are making it much easier for small companies, or even sole developers to rapidly develop and get applications online. The upshot of this is that it's far easier and cheaper to start projects like [Good HQ](https://goodhq.org) than it has ever been in the past, and this is helping to drive the ever increasing number of new tech startups which we've seen over the last couple of years.
