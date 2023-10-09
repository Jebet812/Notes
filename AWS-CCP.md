# AWS Certified Cloud Practitioner 

<details><summary>Cloud Computing</summary>
<p>

## Cloud Computing

**Cloud Computing:** On demand delivery of IT resources over the internet.

***Advantages of Cloud Computing***

* **Go global in minutes:** You can deploy applications around the world in minutes while providing customers with low latency.
* **Trade upfront expense for variable expense:** You only pay for computing resources consumed instead of investing heavily on data centres or servers not knowing you will use them or not.
* **Stop guessing capacity:** Capacity is matched to demand.
* **Benefit from massive economies of scale:** Volume discounts are passed which translates  to lower pay-as-you-go prices.
* **Increased speed and agility:** You can innovate quickly and deliver applications faster.
* **Stop spending money running and maintaining data centers:**

***Benefits of Cloud Computing***

* **High Availability:** High Available systems are desiggned to operate continously without failure for a long time by reducing and managing failure.
* **Elasticity:** You can provision only what need then grow or shrink on demand.
* **Agility:** All services give you access to help you innovate faster, giving you speed to market.
* **Durability:** Data remains intact without corruption.

***Cloud Computing Models***

* **Infrastructure as a Service (IaaS):** Contains asic building locks for cloud IT that can be rented *e.g.* Amazon EC2.
* **Platfrorm as a Service(PaaS):** Enables you develop software using web-based tools without worrying about underlying infrastructure *e.g.* AWS Cloud9.
* **Software as a Service(SaaS):** Provides you with completed product managed and run by a service provider *e.g.* Amazon SageMaker.

***Cloud Computing Deployment Models***

* **Cloud-based deployment:** Migrate all existing applications to cloud or design and build new applications on cloud.
* **On-Prem/Private cloud deployment:** Resources are deployed on prenises by using virtualization and resource management tools.
* **Hybrid deployment:** Connects cloud based resources to on-prem infrastructure. Supported by AWS Direct Connect.


</p>
</details>

<details><summary>Global Networking</summary>
<p>

## Global Networking

* **Regions:** They are isolated geographical areas containing AWS resources. Its characteristics are: </br>
      - They are fully independent and isolated.</br>
      - They are resource and service specific.</br>
When choosing a region for services, data and application consider these factors:</br>
      - Compliance.</br>
      - Proximity of customers.</br>
      - Available services/features within a region.</br>
      - Pricing.</br>

* **Availability Zones:** A single or a group of data centres within a region. It contains servers which you can rent and is where you provision resources and deploy applications. Its characteristics are:
     - They are physically separated.
     - They are connected through low latency links.
     - They are fault tolerant.
     - They allow for high availability.

* **Edge Locations:** Locations used to store cached copies of content close to customers for faster delivery. This is made possible through *Amazon CloudFront* (is a content delivery network to deliver data, video, applications and APIs with low latency and high transfer speeds </br>
It *reduces latency* (time between user request and resulting response) and *speeds up delivery of application.*</br>
There are more edge locations than regions and availability zones.

### How to Provision AWS Resources.


 
</p>
</details>


</p>
</details>

<details><summary>Technology</summary>
<p>

## Technology.

### Compute 

#### Elastic Compute Cloud (EC2)
Allows you one to reny and manage virtual servers in the cloud. It provides secure, resizable compute capacity in the cloud as EC2 instances.<br/> 
*Servers* are the physical compute hardware running in a data center.<br/> 
*Instances* are not considered serverless because they exist on a server in a datacentre.<br/> 

***Accesing EC2 Instance**
1. AWS Management Console:
2. Secure Shell (SSH):
3. EC2 Instance Connect (EIC):
4. AWS Systems Manager

#### Amazon Lightsail

#### AWS Lambda

#### Containers
1. Elastic Container Service (ECS)
2. Elastic Container Registry (ECR)
3. ECS Fargate
4. Elastic Kubernetes Servise (EKS)

#### High Performance Computing Services
1. Nitro System
2. Bare Metal inatances

### Storage

#### Block Storage

#### File Storage 


#### Object Storage 
##### Amazon Simple Service Storage (S3)


### Databases
1. **Amazon Relational Database Service(RDS):** service that enables managing your databases in the cloud, not a database itself. It supports 6 SQL database types Amazon Aurora, PostgreSQL, MySQL, MariaDB, Oracle Database, and SQL Server.
2. **Amazon Dynamo DB:**  a fully managed, serverless, key-value NoSQL database designed to run high-performance applications at any scale. DynamoDB offers built-in security, continuous backups, automated multi-Region replication, in-memory caching, and data import and export tools. Is *serverless* For cases requiring high performance and scaling.
3. **Amazon Aurora:** Enterprise-class relational database. Compatible with MySQL and PostgreSQL. 5X faster than starndard MySQL and 3X than starndard PostgreSQL.
4. **Amazon RedShift:** Data warehousing service you can use for big data and analytics.
**Additional Database Services**
* Amazon DocumentDB (with Mongo DB compatibility)
* Amazon Neptune
* Amazon Quantum Ledger Database
* Amazon Managed Blockchain
* Amazon ElasticCache
* Amazon DynamoDB Accelerator

### Cloud Architecture
* ***High Availability*** Ability for service to remain available y ensuring no single point of failure. Ensure certain level of performance.
1. **Elastic Load Balancer:** automatically distributes your incoming traffic across multiple targets, such as EC2 instances, containers, and IP addresses, in one or more Availability Zones. <br>
Monitors the health of its registered targets, and routes traffic only to the healthy targets.<br> 
Elastic Load Balancing scales your load balancer capacity automatically in response to changes in incoming traffic.




</p>
</details>


<details><summary>Security</summary>
<p>

## Security

### Shared Responsibility Model
#### AWS Responsiilty (Security Of The Cloud)

#### Customer's Responsibility (Security In The Cloud)

### User Permsissions and Acces
1. **AWS Root User**
2. **AWS Identity and Access Management**
3. **IAM Users**
4. **IAM Policies** 
5. **IAM Groups**
6. **IAM Roles**

### AWS Organizations
- Provides centaralized management of AWS accounts
- Consolidated billing (bulk discounts)
- Implement hierachal groupingg of accounts
Use *service control policies* to centrally control pernmissions for the accounts in organization.

### Compliance 
1. **AWS Artifact:** service that provides on demand access to AWS security and compliance reports and select online agreements. Has two sections:
* *AWS Artifact Agreements*
* *AWS Artifact Reports* 

To get resources, get whitepapers, documentation and learn more about AWS compliance go to *compliance centre*

### Denial of  Service Attacks
1. **AWS Shield:** protects applications against DDoS attacks. Provides two levels;
* *AWS Shield Starndard:* protects all customers from common, frequent attacks at no cost.
* *AWS Shield Advance:* paid service that provides detailed attack diagnosis and ability to detect and mitigate sophisticated attacks. For higher levels of protection against attacks targeting your web applications running on Amazon EC2, Elastic Load Balancing (ELB), CloudFront, and Route-53 resources, you can subscribe to AWS Shield Advanced. 
2. **AWS Config:**

### Encryption
1. **AWS Key Management Service(KMS):** enables creation and management of encryption keys. Intergrates with *AWS Cloudtrail* to provide logs to help meet regulation and compliance.

### Additional Security Services
1. **Amazon Inspector:**
2. **Amazon GuardDuty:**
3. **AWS WAF:**

### Security Design Principles
1. Implement a strong identity foundation.
2. Enable traceability.
3. Apply security at all layers.
4. Automate security best practices.
5. Protect data in transit and at rest.
6. Keep people away from data.
7. Prepare for security events.






