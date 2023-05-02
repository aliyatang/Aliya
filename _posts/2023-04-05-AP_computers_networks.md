---
toc: true
comments: true
layout: post
title: Computers and Networks (Unit 4)
description: Add Definitions from Unit 4 Computer Systems and Networks
image: /images/apcsp.png
categories: []
type: ap
week: 29
---

## Requirements
> Work through College Board Unit 4... blog, add definitions, and pictures.  Be creative, for instance make a story of Computing and Networks that is related to your PBL experiences this year.


### How a Computer Works
> As we have learned, a computer needs aa program to do something smart.  The sequence of a program initiates a series of actions with the computers Central Processing Unit (CPU). This component is essentially a binary machine focussing on program instructions provided.  The CPU retrieives and stores the data it acts upon in Random Access Memory (RAM). Between the CPU, RAM, and Storage Devices a computer can work with many programs and large amounts of data.

List specification of your Computer, or Computers if working as Pair/Trio
- Processor GHz: Apple M2 2.4 GHz
- Memory in GB: 8 GB
- Storage in GB: 500 GB Flash Storage
- OS: macOS Montery Version 12.5

Define or describe usage of Computer using Computer Programs. Pictures are preferred over a lot of text.  Use your experience.
- Input devices: send info to a computer system for processing
- Output devices: reproduces/displays result of that info
![This is an image](https://static.javatpoint.com/computer/images/input-device-vs-output-device.png)

- Program File: file containing code or instructions that can be executed by computer for a task or goal
![This is an image](https://www.partitionwizard.com/images/uploads/articles/2019/12/program-files-x86-vs-program-files/program-files-x86-vs-program-files-1.png)

- Program Code: set of instructions writtenin programming lanuage that can create an executable program
![This is an image](https://upload.wikimedia.org/wikipedia/commons/3/39/C_Hello_World_Program.png)

- Processes: See processes running in activity monitor (on mac), they are areas of program activity thatn normally run parallel to each other
![This is an image](https://help.apple.com/assets/63D42DEC71F9CB56F3286525/63D42DF271F9CB56F328652E/en_US/91d4318f871a7c26b58074fc3f94bf8d.png)

- Ports: virtual pont where network connections start and end
![This is an image](https://networkinterview.com/wp-content/uploads/2019/07/PORT.jpg)

- Data File: contains actual data/view of the data, only meant to be read or viewed, NOT executed (such as word file, excel file)
![This is an image](https://www.researchgate.net/publication/220913298/figure/fig3/AS:667773554401285@1536221030394/Data-file-example-Access-format.ppm)

- Inspect Running Code: examining a program's execution in real time to check for errors, monitor performance, gather info about its behavior

- Inspect Variables: examining a variables value or contents at a specific point in a program's execution to see its role/behavior in the program. This an be done with debugging.


![Computer Hardware]({{site.baseurl}}/images/cpu.jpeg)


### The Internet
> Watch/review College Board Daily Video for 4.1.1

- Essential Knowledge
    - A computing device is a physical artifact that can run a program. Some examples include computers, tablets, servers, routers, and smart sensors.
    - A computing system is a group of computing devices and programs working together for a common purpose.
    - A computer network is a group of interconnected computing devices capable of sending or receiving data.
    - A computer network is a type of computing system. 
    - A path between two computing devices on a computer network (a sender and a receiver) is a sequence of directly connected computing devices that begins at the sender and ends at the receiver.
    - Routing is the process of finding a path from sender to receiver.
    - The bandwidth of a computer network is the maximum amount of data that can be sent in a fixed amount of time.
    - Bandwidth is usually measured in bits per second

- Complete Vocabulary Matching Activity.  Incorporate this into your learnings from year.  To analyze measure path and latency use `traceroute` and `ping` commands from Linux Terminal.  
    - Path: a
    - Route: e
    - Computer System: b
    - Computer Device: c
    - Bandwidth: d
    - Computer Network: f

![This is an image](https://github.com/aliyatang/Aliya/blob/master/images/2023-05-01-pic1.png?raw=true)

All of these terms are part of the internet and computers, which we use everyday and are a part of a learnings from the year. We use computer systmes and computer devices in class, for example, our laptops and working together with others on laptops. Another example is when connecting CRUD backend and frontend, the path is the link to the frotend page to access it. IP (internet protocol) is responsible for guiding message routing (routes) between systems by dividing them into packets, which are reconstructed by the network, aided by computer networks connecting servers and computers holding data.

> Watch/review College Board Daily Video 4.1.2

- Complete True of False Questions
![This is an image](https://github.com/aliyatang/Aliya/blob/master/images/2023-05-01-pic2.png?raw=true)

- Essential Knowledge
    - The internet is a computer network consisting of interconnected networks that use standardized, open (nonproprierary) communication protocols.
    - Access to the internet depends on the ability to connect a computing device to an internet connected device.
    - A protocol is an agreed-upon set of rules that specify the behavior of a system.
    - The protocols used in the internet are open, which allows users to easily connect additional computing devices to the internet.
    - Routing on the internet is usually dynamic; it is not specified in advance
    - The scalability of a system is the capacity for the system to change in size and scale to meet new demands.
    - The internet was designed to be scalable
    - Information is passed through the internet as a data stream. Data streams contain chunks of data, which are encapsulated in packets. 
    - Packets contain a chunk of data and metadata used for routing the packet between the origin and the destination on the internet, as well as for data reassembly.
    - Packets may arrive at the destination in order, out of order, or not at all
    - IP, TCP and UDP are common protocols used on the internet.
    - The world wide web is a system of linked pages, programs, and files.
    - HTTP is a protocol used by the world wide web
    - The world wide web uses the internet

- Go over AP videos, vocabulary, and essential knowledge.  Draw a diagram showing the internet and its many levels. A preferred diagram would using your knowledge of frontend, backend, deployment, etc.  Picture would highligh vocabulary by illustration. The below illustration have some ideas

![Full Stack]({{site.baseurl}}/images/fullstack.png)

![This is an image](https://github.com/aliyatang/Aliya/blob/master/images/2023-05-01-pic3.png?raw=true)


- Often we draw pictures of machines communicating over the Internet with arrows.  However, the real communication goes through protocol layers and the machine and then is trasported of the network.   For College Board and future Computer Knowledge you should become familiar with the following ...

```
     User Machine  <---> Frontend Server <---> Backend Server
    +-----------+         +-----------+         +-----------+
    |  Browser  |         |  GH Page  |         |   Flask   |
    +-----------+    ^    +-----------+    ^    +-----------+
    |    HTTP   |    |    |    HTTP   |    |    |    HTTP   |
    +-----------+    |    +-----------+    |    +-----------+
    |    TCP    |    |    |    TCP    |    |    |    TCP    |   
    +-----------+    |    +-----------+    |    +-----------+
    |     IP    |    V    |     IP    |    V    |     IP    |
    +-----------+         +-----------+         +-----------+
    |  Network  |  <--->  |  Network  |  <--->  |  Network  |
    +-----------+         +-----------+         +-----------+
```

The "http" layer is an application layer protocol in the TCP/IP stack, used for ***communication between web browsers and web servers***. It is the protocol used for transmitting data over the World Wide Web.

The "transport" layer (TCP) is responsible for providing reliable data transfer between applications running on different hosts.  The TCP protocol segments the data into smaller ***chunks called "segments"***. Each segment contains a sequence number that identifies its position in the original stream of data, as well as other control information such as source and destination port numbers, and checksums for error detection.

The "ip" layer is responsible for packetizing data received from the TCP layer of the protocol stack, and then ***encapsulating the data into IP packets***. The IP packets are then sent to the lower layers of the protocol stack for transmission over the network.

The "network" layer is responsible for ***routing data packets between networks*** using the Internet Protocol (IP). This layer handles tasks such as packet addressing and routing, fragmentation and reassembly, and ***network congestion*** control.


### Fault Tolerance
> Watch both Daily videos for 4.2

- Complete the network activity, summarize your understanding of fault tolerance.



Daily Video 1

* For each of these examples, keep in mind: More than one path available for paths between each of the devices = fault tolerant

1. Yes, there is more than one path available, at least two paths, for each of the other devices.
![This is an image](https://github.com/aliyatang/Aliya/blob/master/images/2023-05-01-pic4.png?raw=true)
* picture to get the idea... not gonna add pictures for all

2. No, for F there is only one path to it, from C to F. If that one is broken, then connection to F is lost. This is not fault tolerant.

3. No, for A there is only one path to it, from A to G. If that one is broken, then connection to A is lost. This is not fault tolerant.

Daily Video 2

Which of the following is NOT a benefit of a fault tolerant network?

- a. data has more than one path to travel from one device to another
- b. if part of the network fails, the network ca still function using other paths
- c. data will only take one route from one device to another, no matter the number of routes avaiable
- d. more devices creates more connections and makes the network stronger

The answer is C, if the data only takes one single route that defeats the purpose of fault tolerance and using multiple routes to travel to make the network stronger

![This is an image](https://github.com/aliyatang/Aliya/blob/master/images/2023-05-01-pic5.png?raw=true)
I see here that A only has one path to it, so I probably want to have a connection from A to something else. So, a connection from A to B would be best here. Answer choice A.

Fault tolerance 

Fault tolerance is a process that enables an operating system to respond to a failure in hardware or software. This fault-tolerance definition refers to the system's ability to continue operating despite failures or malfunctions.



### Parallel and Distributed Computing
> Review previous lecture on Parallel Computing and watch Daily vidoe 4.3.  Think of ways to make something in you team project to utilize Cores more effectively.  Here are some thoughts to add to your story of Computers and Networks...

- What is naturally Distributed in Frontend/Backend archeticture? 
The frontend is distributed across multiple devices, while the backend is centralized and runs on dedicated servers or cloud-based infrastructure.

- Analyze this command in Docker: ```ENV GUNICORN_CMD_ARGS="--workers=1 --bind=0.0.0.0:8086"```.   Determine if there is options are options in this command for parallel computing within the server that runs python/gunicorn.  Here is an [article](https://medium.com/building-the-system/gunicorn-3-means-of-concurrency-efbb547674b7)
It sets an environement variable named GUNICORN_CMD_ARGS, with the value --workers=1 --bind=0.0.0.0:8086. 

The --workers option in the ENV GUNICORN_CMD_ARGS command sets the number of worker processes that Gunicorn will use to handle incoming requests. A value of 1 means that Gunicorn will use a single worker process. This option controls the number of requests that can be handled simultaneously, but it is not related to parallel computing within the server that runs Python/Gunicorn. Using more than 1 worker process can improve the server's capacity to handle multiple requests at once.

> Last week we discussed parallel computing on local machine.  There are many options.  Here is something to get parallel computing work with a tool called Ray.
- Review this [article](https://www.anyscale.com/blog/writing-your-first-distributed-python-application-with-ray)...  Can you get parallel code on images to work more effectively?  I have not tried Ray.
To process images faster, you can use a parallelization technique called data parallelism, where the same calculation is applied to multiple parts of the image simultaneously

- Code example from ChatGPT using squares.  This might be more interesting if nums we generated to be a lot bigger.

```python
import ray

# define a simple function that takes a number and returns its square
def square(x):
    return x * x

# initialize Ray
ray.init()

# create a remote function that squares a list of numbers in parallel
@ray.remote
def square_list(nums):
    return [square(num) for num in nums]

# define a list of numbers to square
nums = [1, 2, 3, 4, 5]

# split the list into two parts
split_idx = len(nums) // 2
part1, part2 = nums[:split_idx], nums[split_idx:]

# call the remote function in parallel on the two parts
part1_result = square_list.remote(part1)
part2_result = square_list.remote(part2)

# get the results and combine them
result = ray.get(part1_result) + ray.get(part2_result)

# print the result
print(result)

```
