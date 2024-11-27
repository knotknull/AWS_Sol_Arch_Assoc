# AWS Solution Architect Associate Exam Conceptual Study Cards

1. Q: What are the three main types of cloud computing service models?
   A: Infrastructure as a Service (IaaS), Platform as a Service (PaaS), and Software as a Service (SaaS)

2. Q: What is the primary purpose of an AWS Virtual Private Cloud (VPC)?
   A: To provide a logically isolated section of the AWS Cloud where you can launch resources in a virtual network that you define

3. Q: Explain the difference between horizontal and vertical scaling in AWS?
   A: Vertical Scaling: Increasing the size/power of a single resource (e.g., upgrading from t2.micro to t2.large)
      Horizontal Scaling: Adding more resources (e.g., adding more EC2 instances to distribute load)

4. Q: What are the key components of a highly available architecture in AWS?
   A: Multiple Availability Zones, Elastic Load Balancers, Auto Scaling Groups, and distributed database solutions

5. Q: What is the purpose of an Internet Gateway in AWS?
   A: To allow communication between instances in your VPC and the internet, enabling public internet access

6. Q: Describe the difference between Amazon S3 Standard and S3 Glacier storage classes?
   A: S3 Standard: Frequently accessed data with high durability and availability
      S3 Glacier: Long-term, low-cost archival storage with longer retrieval times

7. Q: What is the primary function of AWS Identity and Access Management (IAM)?
   A: To securely control access to AWS services and resources by managing users, groups, roles, and permissions

8. Q: Explain the concept of a Placement Group in Amazon EC2?
   A: A logical grouping of instances that provides enhanced performance and lower network latency through strategic instance placement

9. Q: What are the three types of Elastic Load Balancers?
   A: Application Load Balancer (Layer 7), Network Load Balancer (Layer 4), and Classic Load Balancer (legacy)

10. Q: What is AWS Direct Connect?
    A: A cloud service solution that establishes a dedicated network connection from on-premises networks to AWS

11. Q: Describe the purpose of Amazon CloudWatch?
    A: A monitoring and observability service that provides data and actionable insights for AWS resources and applications

12. Q: What is the difference between public and private subnets in a VPC?
    A: Public subnets have a route to the Internet Gateway and can be directly accessed from the internet
    Private subnets do not have direct internet access and require a NAT Gateway for outbound internet connectivity

13. Q: Explain AWS Lambda and its primary use cases?
    A: Serverless compute service that runs code in response to events without managing servers, ideal for microservices and event-driven architectures

14. Q: What is Amazon RDS and what databases does it support?
    A: Managed relational database service supporting MySQL, PostgreSQL, MariaDB, Oracle, SQL Server, and Amazon Aurora

15. Q: What is the purpose of a NAT Gateway?
    A: To allow instances in a private subnet to access the internet while preventing direct inbound access from the internet

16. Q: Describe the key features of Amazon DynamoDB?
    A: Fully managed NoSQL database with low-latency performance, automatic scaling, and seamless serverless integration

17. Q: What is AWS Storage Gateway?
    A: A hybrid cloud storage service that provides on-premises access to virtually unlimited cloud storage

18. Q: Explain the concept of AWS CloudFormation?
    A: Infrastructure as Code (IaC) service that allows you to model and provision AWS resources using templates

19. Q: What is Amazon ElastiCache used for?
    A: In-memory caching service to improve application performance by caching frequently accessed data

20. Q: Describe the AWS Well-Architected Framework?
    A: A guide for designing and operating reliable, secure, efficient, and cost-effective cloud architectures

21. Q: What is Amazon CloudFront and how does it work?
    A: A content delivery network (CDN) service that distributes content globally with low latency and high transfer speeds

22. Q: Explain the purpose of AWS Elastic Beanstalk?
    A: A service that makes it easy to deploy, manage, and scale web applications and services

23. Q: What is the difference between Spot Instances and Reserved Instances?
    A: Spot Instances: Unused EC2 capacity at discounted rates, can be terminated at any time
    Reserved Instances: Provide a significant discount for a 1 or 3-year commitment to a specific instance type

24. Q: What is AWS Transit Gateway?
    A: A service that simplifies network topology by connecting VPCs, on-premises networks, and remote offices

25. Q: Describe Amazon Elastic Block Store (EBS) and its volume types?
    A: Block-level storage for EC2 instances with volume types including General Purpose (GP2/GP3), Provisioned IOPS (IO1/IO2), and Cold HDD (SC1)

26. Q: What is Amazon Elastic Container Service (ECS)?
    A: A fully managed container orchestration service for running Docker containers

27. Q: Explain the concept of AWS Organizations?
    A: A service for centrally managing and governing multiple AWS accounts

28. Q: What is Amazon Elastic File System (EFS)?
    A: A fully managed, scalable file storage service for use with AWS Cloud services and on-premises resources

29. Q: Describe the purpose of AWS Systems Manager?
    A: A unified service to view and control AWS infrastructure, automate operational tasks, and manage resources

30. Q: What is Amazon S3 Lifecycle Management?
    A: A feature that automatically transitions objects between different storage classes or deletes objects after a specified time

31. Q: Explain AWS Snowball and its use cases?
    A: Physical data transport solution for moving large amounts of data into and out of the AWS Cloud

32. Q: What is Amazon Route 53?
    A: AWS's scalable and highly available Domain Name System (DNS) web service

33. Q: Describe the purpose of AWS Security Hub?
    A: A comprehensive security and compliance center that aggregates, organizes, and prioritizes security alerts

34. Q: What is AWS Step Functions?
    A: A serverless function orchestration service for coordinating multiple AWS services into serverless workflows

35. Q: Explain Amazon Elastic Kubernetes Service (EKS)?
    A: A managed Kubernetes service that makes it easy to run Kubernetes on AWS

36. Q: What is AWS Secrets Manager?
    A: A service for managing, retrieving, and rotating database credentials, API keys, and other secrets

37. Q: Describe the purpose of Amazon Kinesis?
    A: A platform for streaming data on AWS, with services for real-time video, audio, application, and IoT data processing

38. Q: What is AWS Config?
    A: A service that enables you to assess, audit, and evaluate the configurations of AWS resources

39. Q: Explain Amazon GuardDuty?
    A: A threat detection service that continuously monitors for malicious activity and unauthorized behavior

40. Q: What is AWS Trusted Advisor?
    A: A service that provides real-time guidance to help follow AWS best practices on cost optimization, performance, security, and fault tolerance

41. Q: Describe Amazon Redshift?
    A: A fully managed, petabyte-scale data warehouse service optimized for high-performance analysis and reporting

42. Q: What is AWS DataSync?
    A: A data transfer service that simplifies, automates, and accelerates moving data between on-premises storage and AWS storage services

43. Q: Explain Amazon Macie?
    A: A fully managed data security and data privacy service that uses machine learning to discover and protect sensitive data

44. Q: What is AWS Global Accelerator?
    A: A networking service that improves application availability and performance using AWS's global network infrastructure

45. Q: Describe AWS WAF (Web Application Firewall)?
    A: A web application firewall that helps protect web applications from common web exploits

46. Q: What is Amazon Neptune?
    A: A fully managed graph database service for building and running applications that work with highly connected datasets

47. Q: Explain AWS Glue?
    A: A fully managed extract, transform, and load (ETL) service for preparing data for analytics

48. Q: What is Amazon SQS (Simple Queue Service)?
    A: A fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless applications

49. Q: Describe AWS Database Migration Service?
    A: A service that helps you migrate databases to AWS quickly and securely with minimal downtime

50. Q: What is AWS Artifact?
    A: A service that provides on-demand access to AWS' security and compliance reports and select online agreements
