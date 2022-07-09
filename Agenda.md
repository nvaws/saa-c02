# AWS-SAA-C02

## Get Started

- [The NIST definition of cloud computing](https://nvlpubs.nist.gov/nistpubs/Legacy/SP/nistspecialpublication800-145.pdf)
- [Introduction and History of AWS](https://techcrunch.com/2016/07/02/andy-jassys-brief-history-of-the-genesis-of-aws/)
- [Certification Roadmap](https://aws.amazon.com/certification/)
- [AWS Certified Solutions Architect – Associate](https://aws.amazon.com/certification/certified-solutions-architect-associate/)
- [Free tier account creation](https://aws.amazon.com/premiumsupport/knowledge-center/create-and-activate-aws-account/) and [coverage](https://aws.amazon.com/free/)
- [AWS Global Infrastructure](https://aws.amazon.com/about-aws/global-infrastructure/)
- [Regions, Availability Zones](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/using-regions-availability-zones.html) and [Edge Network Locations](https://aws.amazon.com/about-aws/global-infrastructure/regional-product-services/#AWS_Edge_Network_Locations)
- Exploring the AWS Management Console
- [Control your AWS costs](https://aws.amazon.com/getting-started/hands-on/control-your-costs-free-tier-budgets/)
- [Setting up free tier billing alerts](https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/tracking-free-tier-usage.html)
- [AWS Ramp-Up Guide: Architect](https://d1.awsstatic.com/training-and-certification/ramp-up_guides/Ramp-Up_Guide_Architect.pdf)


### Security, Identity, and Compliance

- [IAM](https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction.html)
  - [The AWS Account Root User](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_root-user.html) and [only when to use it](https://docs.aws.amazon.com/general/latest/gr/aws_tasks-that-require-root.html)
  - [MFA](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_mfa_enable_virtual.html#enable-virt-mfa-for-root)
  - [Policies and Permissions](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies.html)
  - [Users](https://docs.aws.amazon.com/IAM/latest/UserGuide/introduction_identity-management.html)
  - [Groups](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_groups.html)
  - [Permissions boundary](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_boundaries.html)
  - [IAM Roles](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_roles.html)
  - [Security best practices in IAM](https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html)
- [KMS](https://docs.aws.amazon.com/kms/latest/developerguide/overview.html), [AWS-managed and Customer-managed CMKs](https://docs.aws.amazon.com/whitepapers/latest/kms-best-practices/aws-managed-and-customer-managed-cmks.html)
- [WAF](https://docs.aws.amazon.com/waf/latest/developerguide/waf-chapter.html)
- [Shield](https://docs.aws.amazon.com/waf/latest/developerguide/shield-chapter.html)
- [Resource Access Manager](https://docs.aws.amazon.com/ram/latest/userguide/what-is.html)
- Amazon Macie
- Amazon GuardDuty
- Amazon Inspector
- AWS Certificate Manager (ACM)
- AWS Directory Service
- AWS Secrets Manager
- AWS Single Sign-On

### Networking and Content Delivery

- [VPC](https://aws.amazon.com/vpc/), 
  - [Subnets](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Subnets.html#vpc-subnet-basics) (Public, Private)
  - [VPC FlowLogs](https://docs.aws.amazon.com/vpc/latest/userguide/flow-logs.html)
  - [RouteTables](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Route_Tables.html)
  - Gateways
    - [Internet Gateway](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Internet_Gateway.html)
    - [NAT Gateway](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-nat-gateway.html), [NAT Instances](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_NAT_Instance.html); [Comparison](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-nat-comparison.html)
    - [VPC Peering](https://docs.aws.amazon.com/vpc/latest/peering/what-is-vpc-peering.html)
    - [Transit Gateway](https://aws.amazon.com/transit-gateway/)
    - [VPC Endpoints](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-endpoints.html) (to be revisited)
    - [Private Link](https://docs.aws.amazon.com/vpc/latest/userguide/endpoint-service.html)
  - [ENI](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/using-eni.html), [ENA](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/enhanced-networking-ena.html), [EFA](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/efa.html) (Comparision)
  - [Elastic IP](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/elastic-ip-addresses-eip.html)
  - [Network ACLs](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-network-acls.html) (Stateless)
  - [Security Groups](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_SecurityGroups.html) (Stateful)
  - [Comparison of security groups and network ACLs](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Security.html)
  - [Site-to-Site VPN](https://docs.aws.amazon.com/vpn/latest/s2svpn/VPC_VPN.html)
  - [Direct Connect](https://docs.aws.amazon.com/directconnect/latest/UserGuide/Welcome.html)
 - [Route 53](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/Welcome.html)
  - [Routing Policies](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy.html)
- [CloudFront](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Introduction.html)
- [API gateway](https://docs.aws.amazon.com/apigateway/latest/developerguide/welcome.html)
- [AWS Global Accelerator](https://aws.amazon.com/global-accelerator/), [workshop](https://intro-to-global-accelerator.workshop.aws/en)
- [Whitepaper](https://d1.awsstatic.com/whitepapers/building-a-scalable-and-secure-multi-vpc-aws-network-infrastructure.pdf) and [video](https://www.youtube.com/watch?v=hiKPPy584Mg) for recap

### Compute

- [EC2](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/concepts.html)
  - Creation Modification, Deletion
- [Userdata, Metadata (Comparison)](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-instance-metadata.html)
- [Elastic Load Balancing](https://docs.aws.amazon.com/elasticloadbalancing/latest/userguide/what-is-load-balancing.html)
  - [ALB](https://docs.aws.amazon.com/elasticloadbalancing/latest/application/introduction.html)
  - [NLB](https://docs.aws.amazon.com/elasticloadbalancing/latest/network/introduction.html)
- [Auto Scaling](https://docs.aws.amazon.com/autoscaling/ec2/userguide/scaling_plan.html)
  - [Launch templates](https://docs.aws.amazon.com/autoscaling/ec2/userguide/launch-templates.html)
  - [Auto Scaling Group](https://docs.aws.amazon.com/autoscaling/ec2/userguide/AutoScalingGroup.html)
  - Scaling Policies
    - [Target tracking policy](https://docs.aws.amazon.com/autoscaling/ec2/userguide/as-scaling-target-tracking.html)
    - [Scheduled scaling policy](https://docs.aws.amazon.com/autoscaling/ec2/userguide/schedule_time.html)
- [EC2 purchasing Options](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/instance-purchasing-options.html), [Tenancy](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/dedicated-instance.html)
- [Elastic Beanstalk](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/Welcome.html)
- [Placement Group](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/placement-groups.html)
- ECS, Fargate [Workshop 1](https://ecs-cats-dogs.workshop.aws/en/), [Workshop 2](https://ecsworkshop.com/)
- EKS, [Workshop](https://www.eksworkshop.com/)
- [Lambda](https://docs.aws.amazon.com/lambda/latest/dg/welcome.html)


### Storage

- [Overview](https://docs.aws.amazon.com/whitepapers/latest/aws-overview/storage-services.html) 
- Block Storage
  - [Instance Stored Volumes](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/InstanceStorage.html)
  - [EBS, EBS Volumes](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AmazonEBS.html)
    - Types
    - Creation, Modification, Deletion.
    - [Snapshot](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EBSSnapshots.html), copying a snapshot.
- Object Storage
- [S3](https://aws.amazon.com/s3/)
  - [Pricing](https://aws.amazon.com/s3/pricing/)
  - [Versioning](https://docs.aws.amazon.com/AmazonS3/latest/dev/Versioning.html)
  - [Static Website Hosting](https://docs.aws.amazon.com/AmazonS3/latest/dev/WebsiteHosting.html)
  - [Pre-signed url](https://docs.aws.amazon.com/AmazonS3/latest/dev/ShareObjectPreSignedURL.html)
  - [ACL](https://docs.aws.amazon.com/AmazonS3/latest/dev/S3_ACLs_UsingACLs.html)
  - [Bucket Policy](https://docs.aws.amazon.com/AmazonS3/latest/dev/using-iam-policies.html) 
  - [S3 Storage Classes](https://aws.amazon.com/s3/storage-classes/)
  - [Object lifecycle management](https://docs.aws.amazon.com/AmazonS3/latest/dev/object-lifecycle-mgmt.html)
  - [Encryption](https://docs.aws.amazon.com/AmazonS3/latest/dev/bucket-encryption.html)
  - [Transfer Acceleration](https://docs.aws.amazon.com/AmazonS3/latest/dev/transfer-acceleration.html)
  - [Replication](https://docs.aws.amazon.com/AmazonS3/latest/dev/replication.html)
  - [Object lock](https://docs.aws.amazon.com/AmazonS3/latest/dev/object-lock.html)
  - [Server access logging](https://docs.aws.amazon.com/AmazonS3/latest/dev/ServerLogs.html)
  - [Avoiding accidental deletion](https://aws.amazon.com/premiumsupport/knowledge-center/s3-audit-deleted-missing-objects/)
- [Data Consistency Model](https://docs.aws.amazon.com/AmazonS3/latest/dev/Introduction.html#ConsistencyModel)
- [Glacier](https://aws.amazon.com/glacier/)
- File Storage
  - [EFS](https://docs.aws.amazon.com/efs/latest/ug/whatisefs.html)
  - [FSx for Windows File Server](https://docs.aws.amazon.com/fsx/latest/WindowsGuide/what-is.html)
  - [FSx for Lustre](https://docs.aws.amazon.com/fsx/latest/LustreGuide/what-is.html)
- [Storage Gateway](https://aws.amazon.com/storagegateway/)

### Application Integration

- [SQS](https://docs.aws.amazon.com/AWSSimpleQueueService/latest/SQSDeveloperGuide/welcome.html)
- [SNS](https://docs.aws.amazon.com/sns/latest/dg/welcome.html)

### Management & Governance

- AWS Auto Scaling
- AWS Backup
- [AWS CloudFormation](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/Welcome.html), [Sample Templates](https://aws.amazon.com/cloudformation/resources/templates/), [AWS Quick Starts](https://aws.amazon.com/quickstart/)
- [AWS CloudTrail](https://docs.aws.amazon.com/awscloudtrail/latest/userguide/cloudtrail-user-guide.html)
- [Amazon CloudWatch](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/WhatIsCloudWatch.html)
- AWS Config
- Amazon EventBridge (Amazon CloudWatch Events), [Decoupling serverless workloads with Amazon EventBridge](https://www.youtube.com/watch?v=VI79XQW4dIM)
- [AWS Organizations](https://docs.aws.amazon.com/organizations/latest/userguide/orgs_introduction.html)
  - Consolidated Billing
  - Service Control Policies
- AWS Resource Access Manager
- AWS Systems Manager
- [AWS Trusted Advisor](https://aws.amazon.com/premiumsupport/technology/trusted-advisor/)


### Database

- [RDS](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Welcome.html)
  - Types, Creation, Modification and Deletion
  - Read Replica
  - [Aurora global database](https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/Concepts.Aurora.GlobalDB.html)
  - [Hands-on Tutorial](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/TUT_WebAppWithRDS.html)
- [DynamoDB](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Introduction.html)
  - [DynamoDB Globle Tables](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/GlobalTables.html)
  - [DAX](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/DAX.html)
- ElastiCache
  - [Redis](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/DAX.html), [Memcached](https://docs.aws.amazon.com/AmazonElastiCache/latest/mem-ug/index.html), [Comparision](https://aws.amazon.com/elasticache/redis-vs-memcached/)
- [Redshift](https://aws.amazon.com/redshift/)

### Migration and Transfer

- AWS Database Migration Service (AWS DMS)
- [AWS DataSync](https://docs.aws.amazon.com/datasync/latest/userguide/what-is-datasync.html)
- AWS Migration Hub
- AWS Server Migration Service (AWS SMS)
- [AWS Snowball](https://docs.aws.amazon.com/snowball/latest/ug/whatissnowball.html)
- AWS Transfer Family


### AWS Billing and Cost Management

- AWS Budgets
- Cost Explorer

### Analytics

- [Amazon Athena](https://docs.aws.amazon.com/athena/latest/ug/what-is.html)
- Amazon Elasticsearch Service (Amazon ES)
- [Amazon EMR](https://docs.aws.amazon.com/emr/latest/ManagementGuide/emr-what-is-emr.html)
- AWS Glue
- Amazon Kinesis
- [Amazon QuickSight](https://docs.aws.amazon.com/quicksight/latest/user/welcome.html)

### Miscellaneous


- [Simple Monthly Calculator](https://calculator.s3.amazonaws.com/index.html), [AWS Pricing Calculator](https://calculator.aws/#/), [AWS TCO Calculator](https://awstcocalculator.com/)


### Study further

- [Well-Architected Framework](https://docs.aws.amazon.com/wellarchitected/latest/framework/wellarchitected-framework.pdf#welcome), [Online free training](https://www.aws.training/Details/Curriculum?id=42037), [WellArchitectedLabs](https://wellarchitectedlabs.com/)
- [AWS Blog](https://aws.amazon.com/blogs/)
- [AWS Knowledge Center](https://aws.amazon.com/premiumsupport/knowledge-center/)
- [Shared Responsibility Model](https://aws.amazon.com/compliance/shared-responsibility-model/)
- [AWS Documentation](https://docs.aws.amazon.com/index.html)
- [AWS Slideshare Channel](https://www.slideshare.net/AmazonWebServices)
- [AWS Samples](https://github.com/aws-samples), [AWS Labs](https://github.com/awslabs), [AWS Workshops](https://workshops.aws/)
- [AWS Serverless Multi-Tier Architectures with Amazon API Gateway and AWS Lambda - Whitepaper](https://docs.aws.amazon.com/whitepapers/latest/serverless-multi-tier-architectures-api-gateway-lambda/welcome.html)
- [Serverless Application Workshop](https://aws.amazon.com/getting-started/hands-on/build-serverless-web-app-lambda-apigateway-s3-dynamodb-cognito/)
- [Application Migration Workshop](https://application-migration-with-aws.workshop.aws/en)
- [AWS Solutions](https://aws.amazon.com/solutions/)
- [AWS Events](https://aws.amazon.com/events/)
- [Ramp-Up Guides](https://aws.amazon.com/training/ramp-up-guides/)
- [AWS YouTube Channel](https://www.youtube.com/channel/UCd6MoB9NC6uYN2grvUNT-Zg) reInvent, breakout sessions, aws.training, [whitepapers](https://aws.amazon.com/whitepapers/?whitepapers/), [customer case studies](https://aws.amazon.com/solutions/case-studies/), [this is my architecture](https://aws.amazon.com/this-is-my-architecture/), [Video Collection](https://awsvideocatalog.com/)
- [AWS Blog](https://aws.amazon.com/blogs/aws/), [AWS Online Tech Talks](https://aws.amazon.com/events/online-tech-talks/)
- [Exam Readiness: AWS Certified Solutions Architect – Associate](https://explore.skillbuilder.aws/learn/course/external/view/elearning/125/exam-readiness-aws-certified-solutions-architect-associate-digital)
