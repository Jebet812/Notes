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

* **Infrastructure as a Service (IaaS):** Contains basic building locks for cloud IT that can be rented *e.g.* Amazon EC2, EC2 Baremetal, Amazon ECS
* **Platfrorm as a Service(PaaS):** Enables you develop software using web-based tools without worrying about underlying infrastructure *e.g.* AWS Cloud9, Elastic Beanstalk
* **Software as a Service(SaaS):** Provides you with completed product managed and run by a service provider *e.g.* Amazon SageMaker, AWS WordDocs. AWS Fargate, AWS Amplify

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

1. **Elastic Compute Cloud (EC2)**
Allows you one to reny and manage virtual servers in the cloud. It provides secure, resizable compute capacity in the cloud as EC2 instances.<br/> 
*Servers* are the physical compute hardware running in a data center.<br/> 
*Instances* are not considered serverless because they exist on a server in a datacentre.<br/> 

* **Accesing EC2 Instance**
1. AWS Management Console
2. Secure Shell (SSH)
3. EC2 Instance Connect (EIC)
4. AWS Systems Manager

* **Amazon EC2 Instance Families**
1. *General purpose*
2. *Compute Optimized*
3. *Memory Optimized*
4. *Accelerated Computing instances*
5. *Storage Optimized*
6. *Storage Optimized*

* **Amazon EC2 Pricing**
1. *On Demand*
2. *Savings Plan*
3. *Reserved Instances*
4. *Spot Instances*
5. *Dedicated Host*

2. **Amazon Lightsail:** managed virtual server service. Friendly version of EC2.

#### Serverless
1. **AWS Lambda:** a serverless, event-driven compute service that lets you run code for virtually any type of application or backend service without provisioning or managing servers.

#### Containers
1. **Elastic Container Service (ECS):** fully managed container orchestration service that simplifies your deployment, management, and scaling of containerized applications.
2. **Elastic Container Registry (ECR):** a fully managed container registry offering high-performance hosting, so you can reliably deploy application images and artifacts anywhere
3. **ECS Fargate:** serverless compute engine for containers. Comaptible with EKS and ECS
4. **Elastic Kubernetes Servise (EKS):** a managed Kubernetes service that makes it easy for you to run Kubernetes on AWS and on-premises

#### High Performance Computing Services
1. Nitro System
2. Bare Metal inatances

### Storage

#### Block Storage

#### File Storage 


#### Object Storage 
1. **Amazon Simple Service Storage (S3):**


### Databases
1. **Amazon Relational Database Service(RDS):** service that enables managing your databases in the cloud, not a database itself. It supports 6 SQL database types Amazon Aurora, PostgreSQL, MySQL, MariaDB, Oracle Database, and SQL Server.
2. **Amazon Dynamo DB:**  a fully managed, serverless, key-value NoSQL database designed to run high-performance applications at any scale. DynamoDB offers built-in security, continuous backups, automated multi-Region replication, in-memory caching, and data import and export tools. Is *serverless* For cases requiring high performance and scaling.
3. **Amazon Aurora:** Enterprise-class relational database. Compatible with MySQL and PostgreSQL. 5X faster than starndard MySQL and 3X than starndard PostgreSQL.
4. **Amazon RedShift:** Data warehousing service you can use for big data and analytics.<br>

***Additional Database Services***
* Amazon DocumentDB (with Mongo DB compatibility)
* Amazon Neptune
* Amazon Quantum Ledger Database
* Amazon Managed Blockchain
* Amazon ElasticCache
* Amazon DynamoDB Accelerator

### Machine Learning and AI Services
1. **Amazon Sagemaker:** fully managed service to build, train and deploy machine learning models at scale. *Frameworks include* Apache MXNet on AWS, TensorFlow on AWS, pYTorch on AWS.
2. **Amazon SageMaker Ground Truth:** is a data labelling service that will have humans lael a dataset that will be used to train machine learning models.
3. **Amazon Augmented AI:** allows you to conduct a human review of machine learning (ML) systems to guarantee precision.
4. **Amazon CodeGuru:** machine learning code analysis service. Performs code reviews and will suggest improvements to be made.
5. **Amazon Lex:** conversion interface service that one can build voice and text chatbots.
6. **Amazon Personalize:** real time recommendation service. Technology used in Amazon to shop.
7. **Amazon Polly:** text-speech service. Upload text and audio file spoken by synthesized voice is generated.
8. **Amazon Rekognition:** image and voice recognition service. Analyze images and videos to detect and label obbjects.
9. **Amazon Transcribe:** speech to text service.
10. **Amazon Textract:** automatically extracts text, handwriting, and data from scanned documents
11. **Amazon Translate:** neural machine learning translation service.
12. **Amazon Comprehend:** it is a Natural Language Processor (NLP) service used to uncover valuable insights and connections in text.
13. **Amazon Forecast:** time-series forecasting service based on machine learning (ML) and built for business metrics analysis.
14. **Amazon Deep Learning AMIs:** provides ML practitioners and researchers with a curated and secure set of frameworks, dependencies, and tools to accelerate deep learning on Amazon EC2. 
15. **Amazon Deep Learning Container:** docker images that are preinstalled and tested with the latest versions of popular deep learning frameworks
16. **AWS DeepComposer:** ML enables musical keyboard.
17. **AWS DeepLens:** video camera that uses deep-learning. 
18. **AWS DeepRacer:** toy race car that can be powered with ML to perform automomous driving.
19. **Amazon Elastic Inference:** allows you to attach low-cost GPU-powered acceleration to Amazon EC2 and SageMaker instances or Amazon ECS tasks, to reduce the cost of running deep learning inference by up to 75%.
20. **Amazon Fraud Detector:** fully managed fraud detection service.
21. **Amazon Kendra:** enterprise ML search engine service. It uses natural language to suggest answers to question instead of jsut simple keyword matching.

### Big Data and Analytics Services
1. **Amazon Athena:** serverless interactive query service. Take CSV and JSON files in S3  bucket and load them to temporary SQL tables which you can run SQL queries,
2. **Amazon CloudSearch:** fully managed search service. Add search to service.
3. **Amazon Elasticsearch Service (ES):** managed Elasticsearch cluster. It is an open source full-text search engine. Robust than CloudSearch but requires more server and operational maintenance.
4. **Amazon Elastic MapReduce (EMR):** used for data analysis and processing. Can create reports like Redshift but suited when transforming unstructured data to structured data on the fly.
5. **Kinesis Data Streams:** real time data streaming data service. For real time analytics, click streams and ingesting data from IoT devices.
6. **Kinesis Firehose:** serverless and simpler version of Data Streams. 
7. **Amazon Kinesis Data Analytics:** allows you run queries against dta that is flowing through real time stream so as to create reports and analysis on emerging data.
8. **Amazon Kinesis Video Streams:** allows to analyze or apply processing on real-time streaming video.
9. **Managed Kafka Service (MSK):** fully managed Kafka Service.
10. **Redshift:** petabyte size data warehouse. Quickly generate analytics or reports from large amount of data.
11. **Amazon Quicksight:** business intelligence (BI) dashboard. Requires little to know programming knowledge and connect to different databases.
12. **AWS Data Pipeline:** automates the movement of data. Move data between compute and storage services.
13. **AWS Glue:** is an Extract, Transform, Load Service. move data from a location that need transformation before getting to the final destination. Like DMS but more robust.
14. **AWS Lake Formation:** centralized, curated and secured repository that stores data until neede.
15. **AWS Data Exchange:** catalogue for third party data sets. You can download for free subscribe or purcase datasets.












### Cloud Architecture
* ***High Availability*** Ability for service to remain available by ensuring no single point of failure. Ensure certain level of performance.
1. **Elastic Load Balancer:** automatically distributes your incoming traffic across multiple targets, such as EC2 instances, containers, and IP addresses, in one or more Availability Zones. <br>
Monitors the health of its registered targets, and routes traffic only to the healthy targets.<br> 
Elastic Load Balancing scales your load balancer capacity automatically in response to changes in incoming traffic.

* ***High Scalability*** Increase capacity based on the increasing demand of traffic, memory and computing power.<br>
- *vertical scaling* - upgrade to bigger server
- *horizontal scaling* - add more servers of the same size

* ***High Elasticity*** Ability to automatically increase or decrease capacity based on the current demand or traffic, memory and computing power
- *scaling out* - add more servers of the same size
- *scaling in* - Removing underutilized servers of the same size
1. **Auto Scaling Groups:** AWS feature that automatically adds and removes servers based on scaling rules you define on metrics

* ***Highly Fault Tolerant:***  Ability for service to ensure there is no point of failure. Prevent the chance of failure
- *fail-overs* when you plan to shift traffic to redundant system incase primary system fails.
1. **RDS Multi-AZ**  run duplicate standby database in another AZ incase primary database fails.

* ***High Durability*** Recover from disaster and prevent loss of data.
1. **CloudEndure Disaster Recovery** replicates machines into low-cost staging area in target AWS account and preffered region for fast recovery.

* ***Business Continuity Plan*** documet outlining how business will operate during unplanned service distruption.
- *Recovery Point Objective* maximum amount of data loss
- *Recovery Time Objective* maximum amount of downtime business can tolerate witout financial loss

* ***Disaster Recovery Options***
1. **Backup & Restore** *(RTO/RPO):hours*
- Lower Priority use cases.
- Provision all AWS Resources
- Restores backup after event
- cost $
2. **Pilot Light** *(RTO/RPO):10min*
- Data live
- Services idle
- Provision some AWS resources and scale after event
- Cost $$
3. **Warm Standby** *(RTO/RPO):minutes*
- Always running but smaller
- Business critical
- Scale AWS resources after event
- Cost $$$
4. **Multi-site active/active** *(RTO/RPO):realtime*
- Zero downtime
- Near zero data loss
- Mission critical servers
- Cost $$$$


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
1. **Amazon Inspector:** automated vulnerability management service that continually scans AWS workloads for software vulnerabilities and unintended network exposure.
2. **Amazon GuardDuty:** threat detection service that continuously monitors your AWS accounts and workloads for malicious activity and delivers detailed security findings for visibility and remediation.
3. **AWS WAF:** helps you protect against common web exploits and bots that can affect availability, compromise security, or consume excessive resources. Uses *web Access Control List(ACL)* to lock or allow traffic.

### Security Design Principles
1. Implement a strong identity foundation.
2. Enable traceability.
3. Apply security at all layers.
4. Automate security best practices.
5. Protect data in transit and at rest.
6. Keep people away from data.
7. Prepare for security events.

</p>
</details>

<details><summary>Pricing, Billing & Support</summary>
<p>

## Pricing, Billing & Support

### Support Plans
1. **Basic Support**
2. **Developer Support**
3. **Business Support**
4. **Enterprise Support**

## Billing and Pricing
1. **Consolidated Billing:** feature of *AWS Organizations* that allows to pay for multiple accounts with one bill<br>
No additional cost<br>
Use *Cost Explorer* to visualize usage for consolidated billing<br>
Allows for *Volume Discounts* the more you use the more you save.
2. **AWS Free-Tier:** allows users to use AWS at no cost 
3. **AWS Credits** equivalent of USD on AWS platform
4. **AWS Cost Explorer**  lets you visualize and manage your AWS costs and usage over time. Offers historical records but also creates forecasts and savings recommendations
5. **AWS Budgets** gives ability to set up alerts if you exceed or are approaching your defines budget. Can be used for forecast costs but is limited compared to Cost Explorer or doing analysis with AWS Cost and Usage Reports along with BI
6. **AWS Budget Reports** used alongside AWS Budget to create and send daily, weekly or monthly reports to monitor performance of AWS Budget emailed to user.
7. **AWS Cost and Usage Report:** generate detailed spreadsheet enabling one understand and analyse AWS costs.
- Places the reports into S3
- Use Athena to turn the report to queriable database.
- Use QuickSight to visualize billing and data as graphs.
8. **Cost Allocation Tags:** optional metadata that can be attached to AWS resource so when you generate out a Cost and Usage Report you can use the data to better analyze your data. Two types of tags user-defined and AWS generated.
9. **Billing Alarms:** create alarms in Cloudwatch to monitor speed.

### Additional Definitions
1. **Service Health Dashboard:** shows the general status of AWS services
2. **AWS Personal Health Dashboard:** provides alerts and guidance for AWS events that might affect your environment. Available for alll customers. You can use alerts to get notified.
3. **AWS Abuse** *AWS Trust & Safety* is ateam that deals specifically with abuses occuring in AWS platform for the following issues spam, port-scanning, Denial-of-Service (DoS) attack, intrusion attempts, hosting prohibited content, distributed content.
4. **Service Level Agreements(SLA):** formal commitment about the expected level of service between a customer and provider. If needs not met customer eligible for compensation in terms of *Financial or Service Credits*
* *Service Level Indicator(SLI)* measure/measurement that indicates what measure of performance is getting at any given time *e.g* uptime, performance, availability, throughput, latency, error rate, durability and correctness
* *Service Level Objective(SLO):* objective the provider has agreed to meet. Represented as a specific percentage over a period of time
5. **AWS Partner Network:** global partner program for AWS. Joining APN will open org for business oppotunities and allows exclusive training and marketing events. You can be:
- *Consulting Partner* help companies utilize AWS.
- *Technology Partner* build technology on top of AWS as a service offering.<br>
Partner belongs to specific tier: *Select, Advanced or Premier.*
The tiers have different knowledge requirements.
6. **AWS Pricing APIs** There are two versions of API thata you can use to progammatically access pricing info
- *Query API* pricing API via JSON
- *Batch API* price list API via HTML

* You can subscribe to *Amazon Simple Notification Service(SNS)* notifications to get alerts when prices for service change.


</p>
</details>

<details><summary>Monitoring and Analytics</summary>
<p>

## Monitoring and Analytics
1. **AWS Trusted Advisor** recommendation tool that automatically and actively monitors AWS account and provide actional recommendation.<br>
7 Trusted Advisor Checks (*MFA root account, security groups, s3 bucket permissions, RDS Public Snapshots, IAM use, service limits*) for basic and developer ad all for business and enterprise.

*Categories of Trust Advisor*
* Cost Optimization
* Performance
* Security
* Fault Tolerance
* Service Limits
2. **AWS Cloudwatch:**
3. **AWS Cloudtrail:**

</p>
</details>






