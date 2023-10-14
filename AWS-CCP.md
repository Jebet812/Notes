# AWS Certified Cloud Practitioner 

<details><summary>Cloud Concepts</summary>
<p>

## Cloud Concepts

### Cloud Computing

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

### Well Architected Framework

***Pillars**
1. **Operational Excellence:** ability to support development and run workloads effectively, gain insight into their operations, and to continuously improve supporting processes and procedures to deliver business value.<br>

*design principles*
- Perform operations as code.
- Make frequent, small, reversable changes.
- Refine operations procedures frequently
- Anticipate failure.
- Learn from all operational failures.
2. **Security:**bility to protect data, systems, and assets to take advantage of cloud technologies to improve your security.<br>

*design principles*
- Implement a strong identity foundation.
- Maintain traceability.
- Apply security at all layers.
- Automate security best practices.
- Protect data in transit and at rest.
- Keep people away from data.
- Prepare for security events.
3. **Reliability:** ability of a workload to perform its intended function correctly and consistently when it’s expected to. This includes the ability to operate and test the workload through its total lifecycle. <br>

*design principles*
- Automatically recover from failure.
- Test recovery procedures.
- Scale horizontally to increase aggregate workload availability.
- Stop guessing capacity.
- Manage change in automation.
4. **Performance efficiency:** ability to use computing resources efficiently to meet system requirements, and to maintain that efficiency as demand changes and technologies evolve.<br>

*design principles*
- Democratize advanced techniologies.
- Go global in minutes.
- Use serverless architectures.
- Experiment more often.
- Consider mechanical sympathy.
5. **Cost optimization:** includes the ability to run systems to deliver business value at the lowest price point.<br>

*design principles*
- Implement Cloud Financial Management.
-  Adopt a consumption model.
- Measure overall efficiency.
- Stop spending money on undifferentiated heavy lifting.
- Analyze and attribute expenditure.
6. **Sustainability:** focuses on environmental impacts, especially energy consumption and efficiency, since they are important levers for architects to inform direct action to reduce resource usage.<br>

*design principles*
- Understand your imapact.
- Establish sustainaility goals.
- Maximize utilization.
- Anticipate and adopt new, more efficient hardware and software offerings.
- Use managed services.
- Reduce the downstream impact of your cloyd workloads.

### Cloud Adoption Framework (CAF)

**Advantages of CAF**

*** Capabilities and Perspectives***
1. *Business Perspective* IT alignes with business needs and the IT investments can demonstate business results.
2. *People perspective* help organizations more rapidly evolve to a culture of continous growth, learning.
3. *Governance perspective* ensure skills and process align with IT strategy and goals with business strategy and goals.
4. *Platform perspective* understand and communicate nature of IT systems and their relationships.
5. *Security perspective* ensure organization meets its security objectives.
6. *Operations perspective* align and support the operations of business and how business will be conducted.<br>

***Benefits of CAF***
- Reduced business risk
- Improved environmental, social,
and governance (ESG) performance
- Increased revenue
- Increased operational efficiency<br>

***How it works***
- **Envision:** Identify and prioritize transformation opportunities in line with your strategic objectives. 
- **Align:** assess your rediness to architect, build, secure & operate your modern data platform. Identify capability gaps and cross-organizational dependencies.
- **Launch:** grow your legacy and develop new modern applications. Deliver pilots in production and demonstrate incremental business value.  Pilots should be highly impactful and when successful they will influence future direction.
- **Scale:** Expand pilots and business value to desired scale and ensure that the business benefits associated with your cloud investments are realized and sustained.

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

* **Edge Locations:** Locations used to store cached copies of content close to customers for faster delivery. This is made possible through **Amazon CloudFront** (is a content delivery network to deliver data, video, applications and APIs with low latency and high transfer speeds<br>
CloudFront also integrates with AWS WAF, a web application firewall that helps protect web applications from common web exploits, and AWS Shield, a managed DDoS protection service that safeguards web applications running on AWS</br>
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
- **Amazon Machine Image:** predefined configuration for a virtual machine. Includes the number of CPUs, amount of memory RAM, amount of network bandwidth, the OS.

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
- *On Demand* short term, irregular workloads that cannot be interrupted.
- *Savings Plan* 
- *Reserved Instances* steady-state, predictable usage. 1 yr to 3yr contract. Starndard 75% or 54% convertible
- *Spot Instances* flexible start and end times that can be interrrupted
- *Dedicated Host*physical servers capacity fully dedicated to use.

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

- **AWS Elastic Beanstalk:** makes it even easier for developers to quickly deploy and manage applications in the AWS Cloud. Developers simply upload their application, and Elastic Beanstalk automatically handles the deployment details of capacity provisioning, load balancing, auto-scaling, and application health monitoring.

### Networking Services.
1. **Amazon Virtual Private Cloud(VPC):** lets one provision logically isolated section of AWS cloud where you can launch AWS resources in a virtual network that you define.
- **Subnets:** logical partition of an IP network into smaller network segments that allows one group resources together. Can be *private subnet* (access to internet) or *public subnet* (no access to internet).<br>

***security in a VPC***
- **Network Access Control Lists(NACLs:)** acts as virtual firewall at the sunet level. *Allow or Deny rules.* They offer *stateless packet filtering* meaning they do not remember previous decisions made hence has to check packets that cross the subnet border each way (inbound and outbound).
- **Security Groups:** acts as virtual firewall at the instance level. *Create only Allow rules. They offer *stateful packet filtering* meaning they remember previous decisiond made for incoming packets. It only checks inbound traffic.<br>
2. **Route Tables:** determines where network traffic from your subnets are directed. Contains set of rules that you configure to direct network traffic from subnet. Each suunet must be associated with a route table.
3. **Internet Gateway:** enables access to internet.
4. **AWS Direct Connect:** enables a dedicated prIvate connection between the data centre and VPC (very fast connection)
5. **AWS Virtual Private Network:** a secure connection etween on-premise, remote offices, mobile employees.
6. **Private Links (VPC Interface Endpoints):** provides private connectivity between virtual private clouds (VPCs) and your on-premises networks without exposing your traffic to the public internet.
7. **Network Address Translation:** enables instances in private cloud to connect to internet or other AWS resources ut prevents public internet access from initiating the connection.
8. **VPC Peering:** enables you privately route traffic between VPCs.
9. **AWS CloudFront:** content delivery network (CDN) to customers around the world with low latency and high transfer speeds.
10. **AWS Global Accelerator:** networking service that helps improve application availability, performance, and security using the AWS global network.
11. **Amazon Route53:**  highly available and scalable Domain Name System (DNS) web service. Route 53 connects user requests to internet applications running on AWS or on-premises. You can register domain name on it too.



### Storage

#### Block Storage
1. **Amazon Elastic Blockstore(EBS):** service that provides block storage volume. Use *EBS Snapshot* to back up its data. It does *incremental* backups (backups data that changed since most recent snapshot). 
#### File Storage 


#### Object Storage 
1. **Amazon Simple Service Storage (S3):** Object storage built to retrieve any amount of data from anywhere. Cost attributed to storage class andsize of gigabyte of objects stored.

***S3 storage classes**
-  *S3 Standard* for general-purpose storage of frequently accessed data 
- *S3 Intelligent-Tiering* for data with unknown or changing access patterns. uses machine learning. Not accessed in 30 days moves to S3 IA
- *S3 Standard-Infrequent Access (S3 Standard-IA)* infrequent accesed data. 3AZs and has retrieval fee. 
- *S3 One Zone-Infrequent Access (S3 One Zone-IA)* for long-lived, but less frequently accessed data. Only one AZ. Has retieval fee.
- *S3 Glacier* for long-term archive and digital preservation. Retrieve data minute to hours
- *S3 glacier Deep Archive* lowest storage class. Retrieve data in hours.

* **Amazon S3 Transfer Acceleration:** enables fast, easy, and secure transfers of files over long distances between your client and an S3 bucket. Transfer Acceleration takes advantage of Amazon CloudFront’s globally distributed edge locations. As the data arrives at an edge location, data is routed to Amazon S3 over an optimized network path.
#### ***Other Definitions***
1. **AWS Storage Gateway:** allows you to build a data warehouse on the cloud. Hybrid cloud storage services that provide on-premises access to virtually unlimited cloud storage.
2. **AWS Snow Family:** storage and compute devices to move data in and out of cloud
- *AWS Snowcone:* 8TB storage in HDD and 14TB storage in SSD
- *AWS Snowball Edge* storage optimized 80TB and compute optimized 39.5TB
- *AWS Snowmobile* 100PB storage
3. **AWS Backup:**

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
* **Amazon ElasticCache:** add caching layer on top of database to help reduce readtimes of common requests. Comes in Redis and Memcache.
* Amazon DynamoDB Accelerator


### Application Intergration Services
1. **Amazon Simple Notification Service(SNS):** is a pu-sub messaging system which sends notifications via various fomats. Push messages sent to subcribers.
2. **Amazon Simple Queue Service (SQS):** is a queueing service send events in a queue and other applications pull the queue for messages. It offers a reliable, highly-scalable hosted queue for storing messages as they travel between applications or microservices. It moves data between distributed application components and helps you decouple these components
3. **AWS Step Functions:** a visual workflow service that helps developers use AWS services to build distributed applications, automate processes, orchestrate microservices, and create data and machine learning (ML) pipelines.
4. **Amazon EventBridge:**serverless event bus that makes it easy to connect applications together from your own application, third party services and AWS services.
5. **Kinesis:** real time dtreaming data service
6. **Amazon MQ:** managed message broker service that uses ApacheActiveMQ.
7. **Managed Kafka Service(MSK):** fully managed Kafka Service.
8. **API Gateway:** a fully managed service that makes it easy for developers to create, publish, maintain, monitor, and secure APIs at any scale.
9. **AppSync:** fully managed GraphSQL service.


### Machine Learning and AI Services
1. **Amazon Sagemaker:** fully managed service to build, train and deploy machine learning models at scale. *Frameworks include* Apache MXNet on AWS, TensorFlow on AWS, pYTorch on AWS.
2. **Amazon SageMaker Ground Truth:** is a data labelling service that will have humans lael a dataset that will be used to train machine learning models.
3. **Amazon Augmented AI:** allows you to conduct a human review of machine learning (ML) systems to guarantee precision.
4. **Amazon CodeGuru:** machine learning code analysis service. Performs code reviews and will suggest improvements to be made.
5. **Amazon Lex:** conversion interface service that one can build voice and text chatbots.
6. **Amazon Personalize:** real time recommendation service. Technology used in Amazon to shop.
7. **Amazon Polly:** text-speech service. Upload text and audio file spoken by synthesized voice is generated.
8. **Amazon Rekognition:** image and voice recognition service. Analyze images and videos to detect and label objects.
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
4. **Amazon Elastic MapReduce (EMR):** used for data analysis and processing. Can create reports like Redshift but suited when transforming unstructured data to structured data on the fly. Helps you analyze and process vast amounts of data by distributing the computational work across a cluster of virtual servers running in the AWS Cloud. 
5. **Kinesis Data Streams:** real time data streaming data service. For real time analytics, click streams and ingesting data from IoT devices.
6. **Kinesis Firehose:** serverless and simpler version of Data Streams. 
7. **Amazon Kinesis Data Analytics:** allows you run queries against dta that is flowing through real time stream so as to create reports and analysis on emerging data.
8. **Amazon Kinesis Video Streams:** allows to analyze or apply processing on real-time streaming video.
9. **Managed Kafka Service (MSK):** fully managed Kafka Service.
10. **Redshift:** petabyte size data warehouse. Quickly generate analytics or reports from large amount of data.
11. **AWS Data Pipeline:** automates the movement of data. Move data between compute and storage services.
12. **AWS Glue:** is an Extract, Transform, Load Service. move data from a location that need transformation before getting to the final destination. Like DMS but more robust.
13. **AWS Lake Formation:** centralized, curated and secured repository that stores data until neede.
14. **AWS Data Exchange:** catalogue for third party data sets. You can download for free subscribe or purcase datasets.
15. **Amazon Quicksight:** business intelligence (BI) dashboard. Requires little to know programming knowledge and connect to different databases or AWS storage services. 

### Developer Tools
1. **AWS AppConfig:** used to automate process of deploying application configuration variable changes to your web app.
2. **AWS CLI:** a tool you download, configure and control AWS services from the commandline and automate scripts.
3. **AWS Cloud 9:** cloud IDE that lets you write, run and debug code.
4. **AWS CloudShell:** makes it easy to securely manage, explore and interact with AWS resources from the browser.
5. **AWS CodeArtifact:** repository service that makes it easy for organizations to securely store, publish and share software packages used in software development process.
6. **AWS CodeBuild:** fully managed continuous integration service that compiles source code, runs tests, and produces ready-to-deploy software packages.
7. **AWS CodeCommit:** secure, highly scalable, fully managed source control service that hosts private Git repositories.
8. **AWS CodeDeploy:** deployment service that automates application deployments to Amazon EC2 instances, on-premises instances, serverless Lambda functions, or Amazon ECS services.
9. **AWS CodePipeline:** a fully managed continuous delivery service that helps you automate your release pipelines for fast and reliable application and infrastructure updates.
10. **AWS CodeStar:** quickly develop, build, and deploy applications on AWS
11. **AWS X-Ray:** allows developers to analyze and debug distributed applications. It provides a detailed view of the applications and their underlying components to help developers identify and troubleshoot issues in real-time. 

### End User Computing
1. **Amazon AppStream 2.0:** fully managed application streaming service that provides users instant access to their desktop applications from anywhere. 
2. **Amazon WorkSpaces:** secure cloud desktop service. You can provision Windows, Amazon Linux or Ubuntu Linux.
3. **Amazon WorkSpaces Web:** fully managed Linux based service to facilitate secure browser access to internal websites and SaaS applications fro m existing web browswes.

### Frontend Web and Mobile
1. **AWS Amplify:** solution that lets front end web and mobile developers build, ship and host full-stack applications on AWS.
2. **AWS AppSync:** facilitates development of applications faster with serverless GraphQL and Pub/Sub APIs.
3. **AWS Device Farm:** application testing device that lets one improve quality of web and mobile apps by testing across a range of desktop browsers and real mobile devices; without having to provision and manage any testing infrastructure.

### Internet of Things (IoT)
1. **AWS IoT Core:**lets you connect billions of IoT devices and route trillions of messages to AWS services without managing infrastructure.
2. **AWS IoT Greengrass:** software that extends cloud capabilities to local devices. Devices can then collect and analyze data closer to the source of information, react autonomously to local events and communicate securely with each other on local networks.

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
1. **AWS Responsiilty (Security Of The Cloud)**

2. **Customer's Responsibility (Security In The Cloud)**

### User Permsissions and Acces
1. **AWS Root User**
2. **AWS Identity and Access Management**lets you create and manage AWS users and groups and use permissions to allow and deny their access to AWS resources. 
3. **IAM Users** end users that log into the console or interact with AWS resources programmatically by clicking UI interfaces.
4. **IAM Policies** JSON documents that grant permissions for specific user, group or role to access service. Policies are attached to *IAM identities.*
5. **IAM Groups** groups users so they share permissions.
6. **IAM Roles** roles grant resources permissions to specific AWS API actions. Associate policies to a role and assign it to an AWS resource.

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


### Encryption
1. **AWS Key Management Service(KMS):** enables creation and management of encryption keys. Intergrates with *AWS Cloudtrail* to provide logs to help meet regulation and compliance.



### Additional Security Services
1. **Amazon Inspector:** automated vulnerability management service that continually scans AWS workloads for software vulnerabilities and unintended network exposure.
2. **Amazon GuardDuty:** threat detection service that continuously monitors your AWS accounts and workloads for malicious activity and delivers detailed security findings for visibility and remediation.
3. **AWS WAF:** helps you protect against common web exploits and bots that can affect availability, compromise security, or consume excessive resources. Uses *web Access Control List(ACL)* to lock or allow traffic.
4. **AWS Security Centre:** a cloud security posture management (CSPM) service that performs security best practice checks, aggregates alerts, and enables automated remediation.
5. **AWS Security Blog:**
6. **AWS Secret Manager:** ps you manage, retrieve, and rotate database credentials, API keys, and other secrets throughout their lifecycles.
7. **Amazon Cognito:** helps you implement customer identity and access management (CIAM) into your web and mobile applications. You can quickly add user authentication and access control to your applications in minutes.


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
 AWS Support is a mix of tools and technology, people, and programs designed to proactively help you optimize performance, lower costs, and innovate faster. 
1. **Basic Support**
2. **Developer Support**
3. **Business Support**
4. **Enterprise Support**


### Billing and Pricing
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
10. **AWS Pricing Calculator:** predict the cost of moving resources from on-premise to the cloud.

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
7. **AWS Activate for Startups:** helps startups bring their ideas to life.
8. **AWS IQ:** customers to quickly find, engage, and pay AWS Certified third-party experts for on-demand project work. 
9. **AWS Managed Service:** helps you adopt AWS at scale and operate more efficiently and securely.



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
2. **AWS Cloudwatch:** a collection of multiple services. Enables one monitor and manage bvarious metrics and configure alarm action based on data from the metrics.
3. **AWS Cloudtrail:** log all API calls between AWS services. develop developer misconfiguration, detect malicious actors and automate responses. Enables operational auditing and risk auditing. (where, when, who, where). Will by default collect logs fr the last 90 days if you need more create a *trail.*
4. **AWS Config:** used to check if resources are configured the way you'd want them to be.
It enables you to assess, audit, and evaluate the configurations of your AWS resources. Config continuously monitors and records your AWS resource configurations and allows you to automate the evaluation of recorded configurations against desired configurations. With Config, you can review changes in configurations and relationships between AWS resources, dive into detailed resource configuration histories, and determine your overall compliance against the configurations specified in your internal guidelines. This enables you to simplify compliance auditing, security analysis, change management, and operational troubleshooting.
5. **AWS X-Ray:** distributed tracing system. You can use to pinpoint issues with microservices. See how data moves from one app to another, how long it took and if it failed to move forward.
6. **AWS Audit Manager:** to map your compliance requirements to AWS usage data with prebuilt and custom frameworks and automated evidence collection.

</p>
</details>






