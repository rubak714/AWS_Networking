# AWS_Networking
AWS Networking steps which aims to network within the AWS Cloud

# AWS Networking Basics
- Configuring and Deploying an Amazon VPC with Multiple Subnets
- AWS Network Connectivity Options(opens in a new tab)
- AWS Network Monitoring and Troubleshooting(opens in a new tab)
- AWS Network Practical Approaches

# For example:

- Amazon Elastic Compute Cloud (Amazon EC2) instances are connected to the network with elastic network interfaces. 
- On premises servers are connected to the network with physical network interface cards and ports.

# Objectives
- Identify and understand the basic functions of each AWS networking service.

- Recognize the relationship between groups of AWS networking services by understanding the functions and business goals of each.

- Describe how networking concepts and protocols are implemented in AWS.

- Recognize ways to balance performance, cost, and availability for different combinations of AWS networking services.

# AWS Networking Services
![1](https://github.com/rubak714/AWS_Networking/assets/101013219/c50d0ba5-8339-4f8d-a8e1-3312ace2a292)
## AWS network services by group
-- Network foundations: Amazon VPC, AWS Transit Gateway, AWS PrivateLink

-- Hybrid connectivity: AWS Direct Connect, AWS Site-to-Site VPN, AWS Client VPN, AWS Cloud WAN

-- Edge networking: Amazon CloudFront, Amazon Route 53, AWS Global Accelerator

-- Application networking: AWS App Mesh, Amazon API Gateway, AWS Cloud Map

-- Networking security: AWS Shield, AWS WAF, AWS Network Firewall, AWS Firewall Manager

# AWS provides guidance with the following:

AWS Well-Architected Framework to build secure, high-performing, resilient, and efficient networks for applications and workloads. The framework is built around six pillars:
* Operational excellence
* Security
* Reliability
* Performance efficiency
* Cost optimization
* Sustainability
The well-architected framework provides a consistent approach for customers and partners to evaluate architectures and implement scalable designs.

- There is no charge for inbound data transfer across all services in all Regions. However, data transfer from AWS to the internet is charged per service, with rates specific to the originating Region.

# Shared responsibility model

![2](https://github.com/rubak714/AWS_Networking/assets/101013219/c529310e-aa0c-498e-a62d-c8282799a654)

# Networking and Content Delivery:
AWS provides networking and content delivery services to run my network and application workloads. These services help to optimize my communications and data transfer with the highest level of security, reliability, and performance.
![3](https://github.com/rubak714/AWS_Networking/assets/101013219/5d2ce645-7597-44c1-9a0b-7cf6eaa80c57)

# Network Foundation Options
https://aws.amazon.com/products/networking/networking-foundations/?nc=sn&loc=2&dn=4
The AWS network foundation options support the foundational building blocks of my design, environment, network, and workloads to ensure that my meet your business goals.
![4](https://github.com/rubak714/AWS_Networking/assets/101013219/e552e8c5-264e-476d-a6d5-a8f99180b84f)
![5](https://github.com/rubak714/AWS_Networking/assets/101013219/3fbca194-d4c3-4609-887c-1dd70a200ec8)
![6](https://github.com/rubak714/AWS_Networking/assets/101013219/1ce2f530-ef9a-40b5-97f3-16a4844db884)
![7](https://github.com/rubak714/AWS_Networking/assets/101013219/4323bd73-fd3e-48f2-96e7-ef1829eb8d37)

"Your Amazon VPC is not your typical data center" by Julie Elkins

If we explore a comparison between Amazon VPC and an on-premises data center, we will see an immediate hardware cost savings.

# Hybrid Connectivity
AWS provides services and hybrid connectivity solutions to link your on premises and AWS networks. This supports a wide range of hybrid architectures and use cases.

![9](https://github.com/rubak714/AWS_Networking/assets/101013219/eba2d0db-2006-44af-8d95-80c2bbb74836)
![10](https://github.com/rubak714/AWS_Networking/assets/101013219/bc49d5b1-4adf-48fa-b141-381efa300e6d)
![11](https://github.com/rubak714/AWS_Networking/assets/101013219/feba71da-4505-499e-a251-e7a3249fa06e)
![12](https://github.com/rubak714/AWS_Networking/assets/101013219/278a9fc3-ecd0-4ffc-a9a2-6f0a534e3ae6)

# Edge Networking
On AWS, edge networking services securely transmit your user-facing data with improved latency globally. When you use the AWS edge networking services, your traffic moves off the internet and behind the AWS global network. Network edge computing removes the need of reaching back to your data centers or the cloud, to the edge of the network. This interconnects your network and provides a path for the exchange of information quicker.
AWS edge networking services sit at the AWS global edge locations and are configured to connect and deliver data with single-digit millisecond AWS network latency.
![13](https://github.com/rubak714/AWS_Networking/assets/101013219/5afec076-8856-41fd-a029-2a8e1195872f)
![14](https://github.com/rubak714/AWS_Networking/assets/101013219/fc36f726-c2f3-4f6f-b3ff-c9110eee809e)
![15](https://github.com/rubak714/AWS_Networking/assets/101013219/bc7f4c03-1a07-4476-b9c7-8e3ccf0a1931)
![16](https://github.com/rubak714/AWS_Networking/assets/101013219/21fa13db-9763-455f-9649-a4e16d712680)
![17](https://github.com/rubak714/AWS_Networking/assets/101013219/b33067ba-8165-47ab-b813-ec34584cb403)

# Application Networking
On AWS, you can improve your application's network architecture with services that provide your traditional and modern applications improved security, availability, performance, and efficient monitoring capabilities. Along with the edge networking services, AWS also offers application networking services to ensure scalability, high availability, improved performance, and security globally. 

![18](https://github.com/rubak714/AWS_Networking/assets/101013219/59be9c31-e3e0-44e4-922e-b4e8de5cf14b)
![19](https://github.com/rubak714/AWS_Networking/assets/101013219/224c0023-d0b5-4c66-96ec-bf142b06891b)
![20](https://github.com/rubak714/AWS_Networking/assets/101013219/738c4a78-b216-45ad-90ff-4a5a390555fd)
![21](https://github.com/rubak714/AWS_Networking/assets/101013219/4664365d-cdf5-47d6-86a2-546364fc25df)
Elastic Load Balancing, AWS Global Accelerator, Amazon API Gateway, AWS App Mesh, and AWS Cloud Map work together to solve your application networking needs.




