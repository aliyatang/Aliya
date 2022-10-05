---
toc: true
layout: post
description: Curl output and problems I ran into
categories: [markdown, week5]
title: AWS Deployment Process
---

First, I ran into a problem when I wanted to pull something from github to my local server. I stopped the local docker processes by using 'sudo docker-compose kill' and then pulled. 

However, after force restarting the web application and dock container, it wouldn't let me run docker compose with 'sudo docker-compose up -d'

![This is an image](https://github.com/aliyatang/Aliya/blob/master/images/10-4-22-Screenshot1%20copy.png?raw=true)

After reading the error message, I found that I could either:
- Delete the volume
- Change the none type to another type


First, I tried to delete the volume. However, it said that the volume was in use and I couldn't delete it. 

![This is an image](https://github.com/aliyatang/Aliya/blob/master/images/10-4-22-Screenshot2.png?raw=true)

I couldn't figure out why it was doing this, as the volume wasn't in use. 

I tried to change the type, as it said that a volume with the same name uses a type that is different than none - "bind". So next, I changed the type to a different type, "bind". 

![This is an image](https://github.com/aliyatang/Aliya/blob/master/images/10-4-22-Screenshot3.png?raw=true)

This worked. It let me run 'sudo docker-compose up -d' and my webpage was recreated. 

![This is an image](https://github.com/aliyatang/Aliya/blob/master/images/10-4-22-Screenshot4.png?raw=true)

I could also finally verify that my webpage is running with the curl command, "curl http://localhost:8086 | html2text", as it wasn't working before either. 

![This is an image](https://github.com/aliyatang/Aliya/blob/master/images/10-4-22-Screenshot5.png?raw=true)
![This is an image](https://github.com/aliyatang/Aliya/blob/master/images/10-4-22-Screenshot6.png?raw=true)

I was also able to make a change and see the change made in the brower.

Before Change:

![This is an image]()

Change:

![This is an image]()

After Change:

![This is an image]()

Lastly, I was able to use a Domain Name Server(DNS) provider to map my own public IP address to a domain, called "aliyaflask.tk" or "www.aliyaflask.tk".
Here is the link:

[Click Here!](aliyaflask.tk)


