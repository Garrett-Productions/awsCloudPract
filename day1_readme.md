Day 1 Baby! You ready

Foundational - 6 months of fundamental AWS cloud and industry knowledge  - Cloud practitioner
Associate - 1 year - Solutions Architect, Developer, SysOps Administrator

How websites work
- client uses a network between ourserves and the server, the network routes the data and packet to the server and allows the client to view
- a client has an IP address and so does the Server, thats how they find one another

Server
- contains a CPU, does computations to find results
- RAM, stores info and retrieves quickly 
***these two act as a brain
- Storage: Data, we can also use a database to store it in a formatted way and query
- Network: Routers, switch, DNS Servers


IT TERMINOLOGY
- network is a bunch of cables, servers and routers
Rputer
Switch: takes a packet and sends it to the correct client on the network
CPU > ROUTER > SWITCH > DECIDE CLIENT

Data Centers
- traditional! hella servers, like the OG Jeff Bezos day. 

Problems with this 
- pay for rent for the data center 
- pat for colling, maintenance
- adding and replacing hardware
- scaling is limited
- hire a 24/7 team
- what is there is a natural disaster?
- what if you want to scale but cant afford space or money to buy more serves?

SHOUTOUT TO THE CLOUD

CLOUD COMPUTING 
- on demand delivery of CPU, DBS, apps and other IT resources
-  pay-as-you-go
- pick the size and type of computing resources
- you can access all resources instantly 
- cloud gives you a nice interface 
- AWS owns and maintains the hardware required for us to do everything

The cloud is filled with tons of servers, it's omnipresent but not visible.

Examples
- Gmail is a cloud service
- Dropbox is a cloud storage service, built on AWS
- Netflix is built on AWS, video on demand, so is NASA, Activision, Mcdonalds, etc


Deployment Models of the Cloud
1. Private cloud
- used by a single organization, used for security, control, to meet certian business needs
2. Public Cloud
- Cloud services owned by 3rd party and delivered via internet
- 3 Massive company examples are: Microsoft Azure, Google Cloud and AWS

5 Characteristics of Cloud computing 
1. On demand self service
- users can use whatever without provision
2. Broad network access
- can be accessed by diverse client platformsa
3. Multi-tenancy and resource pooling
- customers can share the same infrastructure and apps with security and privacy, and be serviced from thre same physicsl resource 
4. Rapid elasticity and scalabilty 
- acquire and dispose resources at will, scale based on demand 
5. Measured Service
- users only pay for what they use

6 Advantages of Cloud computing 
1. no CAPEX but OPEX( operational expense )
- pay on demand 
2. Massive Economies of Scale
- AWS is large scale, prices are reduced 
3. Stop guessing capacity 
- scale bassed on actual usage
4. Increase Speed and Agility 
5. Save money on data centers
6. Go global in Minutes
- launch a world wide web app by leveraging the AWS infrastructure

Flexible, Cost effective


------------TYPES OF CLOUD COMPUTING----------------
1. Infrastructure as a Service(IaaS) ***provides basic infrastructure 
- has buidling blocks for cloud IT
- provides the cloud
- flexible 
THIS IS EC2
2. Platform as a Service ***provides almost everything
- no managing, they deploy and manage apps
3. Software as a Service(SaaS) **provides everything
- Completed product that is managed and ran by 3rd party service provider

IaaS
- Amazon EC2
- Azure, Rackspace, Digital Ocean, Linode, 

PaaS
- Elastic Beanstalk (AWS)
- heroku, Google App Engine(GCP), Windows Azure(Microsoft)

SaaS
- rekognition for Machine Learning
- Google Apps(Gmail, Dropbox, Zoom)


Pricing Fundamentals 
- compute: pay for compute time 
- storage: pay for data storage
- Data Transfer: data transfer IN is free, transfer OUT is not

------------------------AWS Cloud Facts-------------------------------
- 2019 did $35 Billion in revenue
- AWS accounted for 47% of the market in 2019, Microsoft was at 22%
- over 1,000,000 users consecutively


--------AWS Global Infrastructure---------
1. AWS Regions
2. AWS availability Zones
3. AWS Data centers
4. AWS Edge Locations/ Points of Presence 


AWS Regions
- regions all over the world
- cluster of data centers
- Most services are region-scoped

How to choose an AWS Region?
* compliance with data governance and legal requirements: data never leaves a region without explicit permission
* Proximity: latency and lag, AUS vs US
* Available Services: new services and features arent available in every region
* Pricing: varies region by region( where am i deploying?)

AWS Availbility Zones
- minimum is 3, max is 6
- each AZ is one or more discrete data centers with redundant power, networking and connectivity 
For ex: In Sydney: the first is ap-southeast-2, ap-southeast-2b and ap-southeast-2c, each with 2 physical data centers
* These are isolated on purpose! If there is a disaster we are good
* They are connected with high bandwidth, ultra low latency networking
All of these zones together form a region