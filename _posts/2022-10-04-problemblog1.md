---
toc: true
layout: post
description: Problems I ran into during Flask/Python Deployment
categories: [markdown, week5]
title: Problem Blog 1
---

First, I ran into a problem when I wanted to pull something from github to my local server. I stopped the local docker processes by using 'sudo docker-compose kill' and then pulled. 

However, after force restarting the web application and dock container, it wouldn't let me run docker compose with 'sudo docker-compose up -d'

![This is an image]()

After reading the error message, I found that I could either:
- Delete the volume
- Change the none type to another type
