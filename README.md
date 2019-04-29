# Introduction to Data Intensive Systems

This project aims to introduce developers to a large-scale distributed systems with more than 10TB of data from academia perspective. 


# Introduction

Because of the internet, cheaper storage and advanced in machine learning algorithm, many companies start looking for insight in their data to improve their bussiness strategy. But data size, nowadays, grow bigger and bigger requiring novel systems to handle. These systems usually are developed by big tech companies; Google, Amazon, MS, or Twitter. They introduced new techniques and well-designed architures which is very interesting and worth leaning.

I am just a newbie to this stuff but I want to note what I have leant to other developer that might interested in this topic. Most of them will be a review and short notes from papers.

## Contributing 

Feel free to sugesst or contribute on any topics you like. If you find some mistake both typo mistakes or totally wrong explanations, please let me know (or just comments or send me a PR).

You can add your own topics by sending me a PR. I promise that I will accept it as soon as possible.  


[![HitCount](http://hits.dwyl.com/chameleonTK/intro-to-data-intensive-systems.svg)](http://hits.dwyl.com/chameleonTK/intro-to-data-intensive-systems.svg)
![](https://img.shields.io/github/license/chameleonTK/intro-to-data-intensive-systems.svg)


## Table of contents
* [Distributed systems](#distributed-systems)
* [Hadoop and MapReduce](#hadoop-and-mapreduce)
* [Spark](#spark)

## Distributed systems
As Tanenbaum,2006 defined it as "a collection of independent computers that appears to the user as a single coherent system." Or in a simple word, it is a group of computers working together to deal with a single task. To make it works, there are several design issues to concern.
* Heterogeneity; make it works with different kind of machines
* Openness; how the system can be extended or new services can be added 
    *  uniform communication mechanisms
    *  published interfaces 
* Security
    *  the number of ways that a system may be attacked is significantly increased 
* Scalability
    * Hiding latency; move data closer to the processing node or avoid blocking requests
    * Distribution
    * Replication
* Failure handling; detect and deal with failure
    * It usually is only partial failure
    * Detecting failures; checksum
    * Masking failures; to hidden or fix 
    * Tolerating failures; not to fail other services
    * Recovery
    * Redundancy
* Transparency; appear to the user as a single system
    * mapping abstract to physical resources
    * Access, Location, Migration, Replication, Concurrency, Failure, and Scaling
* Quality of service;
    * acceptable response time and throughput 

### Software Layers
|        Applications        	|
|:--------------------------:	|
|         Middleware         	|
| Platform (OS and Hardware) 	|



### Distributed systems architecture
1. Centralised: 2-tier / N-tier
2. Decentralised
3. Cluster and Cloud computing
    * physically close, highly connected, homogeneous, one admin domain
4. Grid computing 
    * heterogeneous, multiple domains 


### Hadoop and MapReduce 
[Read](https://dl.acm.org/citation.cfm?id=1327492)


### Spark 
[Read](https://dl.acm.org/citation.cfm?id=1863103.1863113) 
[Read #2](https://dl.acm.org/citation.cfm?id=2228301)


## Storage and Databases
## Graph and Stream Processing
## Resource management
## Scheduling algorithms
## Cloud engineering
## Edge / decentralised
## Machine learning and systems



## Author
[Pakawat Nakwijit](http://curve.in.th); An ordinary programmer who would like to share and challange himself.

## License
This project is licensed under the terms of the MIT license.
