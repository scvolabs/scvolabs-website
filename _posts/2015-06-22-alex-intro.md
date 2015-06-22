---
layout: post
date: 2015-06-22
author: Alex
authorlink: https://twitter.com/anuttgens
title: Developing the SCVO Labs project
excerpt: My first month on the job.
tags: digital open
image: 
---
#New Job!

Hi, this is Alex, lead developer on SCVO Labs. Nice to meet you!

For the last few weeks I've been building a prototype of the underlying system which the SCVO Labs app will be running on.

I'm a Java developer by history, and this is my first time doing full-stack development (i.e. I do all of it, from making the servers work, to ensuring that the Project logo on the website is exactly the right shade of purple), so it's a challenging project, and I'm learning loads!

So far, I've built a prototype based on Angular JS, Java and SQL, and running on Amazon's "AWS" distributed server platform. 

It all works quite nicely, but we're wanting to keep looking around, to ensure we've got the right technologies for the job. That's why Chris (the boss) has instituted what Agile developers refer to as a "Firebreak". This is a period where you stop directly developing the app, and have a look around at the technologies available, and decide if you want to do anything differently. In this case, we're wondering about two things:

1. Could we make everything simpler? Javascript and one of Amazon's databases talk in the same language, JSON. Maybe it would be faster and easier if we made everything talk in this language?
2. There's a new type of database called a Graph Database, which is better at handling complicated networked relationships than a standard SQL Database. Given the very connected communities involved in charities, can we use this technology to give us powerful data?
