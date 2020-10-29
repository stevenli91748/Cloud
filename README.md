
**云原生应用12个类别：编排、应用程序开发、监控、日志记录、跟踪、容器注册、存储和数据库、运行时间、服务发现、服务网格、服务代理、安全以及数据流和消息流**

[AWS 各个方向的学习路径](https://aws.amazon.com/cn/training/learning-paths/?nc2=sb_lp_all)|[AWS官方操作教程集---重要](https://aws.amazon.com/cn/getting-started/hands-on/)|[AWS官方实验教程](https://www.wellarchitectedlabs.com/security/)|[AWS的产品一览](https://aws.amazon.com/cn/?nc2=h_lg)|
---|---|---|---|

[AWS DevOps](https://aws.amazon.com/cn/devops/what-is-devops/?nc1=f_cc)|[AWS 容器](https://aws.amazon.com/cn/containers/?nc1=f_cc)|[官方AWS SDK for Java 2.0 documentation examples](https://github.com/awsdocs/aws-doc-sdk-examples)|
---|---|---|

* [使用 Spring Boot、Amazon DynamoDB 和适用于 Java 的 AWS 开发工具包 2.x 创建您的首个 Web 应用程序 »](https://github.com/awsdocs/aws-doc-sdk-examples/tree/master/javav2/usecases/creating_first_project)
* [使用 Spring Boot、Amazon SQS 和适用于 Java 的 AWS 开发工具包 2.x 创建消息收发 Web 应用程序 »](https://github.com/awsdocs/aws-doc-sdk-examples/tree/master/javav2/usecases/creating_message_application)
* [使用 Spring Boot、Amazon Rekognition 和适用于 Java 的 AWS 开发工具包 2.x 创建图像识别 Web 应用程序 »](https://github.com/awsdocs/aws-doc-sdk-examples/tree/master/javav2/usecases/creating_photo_analyzer_app)
* [使用 Kinesis Data Streams 和适用于 Java 的 AWS 开发工具包 2.x 创建流式应用程序 »](https://docs.aws.amazon.com/sdk-for-java/v2/developer-guide/examples-kinesis.html)



[云原生应用之路——从Kubernetes到Cloud Native](https://jimmysong.io/kubernetes-handbook/cloud-native/from-kubernetes-to-cloud-native.html)|
---|


 [Amason Cloud](https://github.com/stevenli91748/Cloud/blob/master/Amason%20Cloud.md)|[全面刨析云计算体系](https://www.youtube.com/watch?v=8Okv5jyuEj8)|
 ---|---|



[AWS Certified Solutions Architect - Associate 2020 (PASS THE EXAM!)](https://www.youtube.com/watch?v=Ia-UEYYR44s)|[How I Passed 3 AWS Exams in 3 Months 2020](https://www.youtube.com/watch?v=Z-8bVozLo0w)|
---|---|

[AWS Certified Solutions Architect Associate Practice test Exam Dumps 2020---800+ UNIQUE practice questions for AWS Solution Architect Associate certification exam.](https://skillcertpro.com/product/aws-certified-solutions-architect-associate-practice-exam-set-2020/)|
---|

[Build AWS Multi-Tier Architecture Project from Scratch](https://www.youtube.com/watch?v=DoaeNEytnuA&list=RDCMUCCktnahuRFYIBtNnKT5IYyg&start_radio=1&t=2192)|
---|

[AWS CodePipeline tutorial  Build a CI/CD Pipeline on AWS](https://www.youtube.com/watch?v=NwzJCSPSPZs)|
---|

[AWS 上的项目：将整体式应用程序拆分为微服务（使用 Amazon Elastic Container Service、Docker 和 Amazon EC2）](https://aws.amazon.com/cn/getting-started/hands-on/break-monolith-app-microservices-ecs-docker-ec2/)|
---|

# 目录
* [AWS 架构完善的框架和五大支柱](https://aws.amazon.com/cn/getting-started/fundamentals-core-concepts/?e=gs2020&p=gsrc)
  * 1 安全性
    * 1.1 Identity and Access Management (IAM)
      * [IAM](https://aws.amazon.com/cn/iam/)
      * [权限边界](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_boundaries.html)
      * [服务控制策略](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies.html#policies_scp)
      * [基于身份和基于资源的策略](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_identity-vs-resource.html)
      * [访问控制列表](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies.html#policies_acl)
      * [会话策略](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies.html#policies_session)
      * [最小权限原则](https://en.wikipedia.org/wiki/Principle_of_least_privilege)
      * [IAM 策略类型](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies.html)
      * [IAM 最佳实践](https://docs.aws.amazon.com/IAM/latest/UserGuide/best-practices.html#grant-least-privilege)
      * [IAM 操作和资源](https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_policies_actions-resources-contextkeys.html)
    * 1.2 网络安全
      * [Amazon Virtual Private Cloud (VPC)](https://aws.amazon.com/cn/vpc/)云中预置一个逻辑隔离的部分，让您可以在自己定义的虚拟网络中启动 AWS 资源
      * [Application Load Balancer (ALB) ](https://docs.aws.amazon.com/elasticloadbalancing/latest/application/introduction.html)
        * Application Load Balancers
        * Network Load Balancers
        * Classic Load Balancers
      * [AWS Web 应用程序防火墙 (WAF)](https://aws.amazon.com/cn/waf/)保护您的 Web 应用程序免遭常见 Web 漏洞的攻击
      * [安全组](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-security-groups.html)
      * [深度防御](https://en.wikipedia.org/wiki/Defense_in_depth_(computing))
      * [AWS 联网和内容分发](https://aws.amazon.com/cn/products/networking/)
    * 1.3 数据加密
      * [Application Load Balancer (ALB) ](https://docs.aws.amazon.com/elasticloadbalancing/latest/application/introduction.html)
      * [Amazon Key Management Service (KMS)](https://aws.amazon.com/cn/kms/)
      * [客户管理的密钥 (CMK)](https://docs.aws.amazon.com/kms/latest/developerguide/importing-keys-create-cmk.html)
      * [AWS CloudTrail ](https://docs.aws.amazon.com/awscloudtrail/latest/userguide/cloudtrail-user-guide.html)
      * [自定义密钥存储](https://docs.aws.amazon.com/kms/latest/developerguide/custom-key-store-overview.html)
  * 2. 性能效率
      * [实例存储](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/InstanceStorage.html)
      * [已预置的容量](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/HowItWorks.ReadWriteCapacityMode.html)
      * [IOPS](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ebs-io-characteristics.html)
      * [AWS Lambda](https://docs.aws.amazon.com/lambda/?id=docs_gateway)
      * 选择
        * 计算服务类别---计算是处理数据的服务（例如，虚拟机）
          * 基于VM的计算---是大多数人最熟悉的思维模式，但价格可能更高，并且需要更多维护
            * [EC2](https://docs.aws.amazon.com/ec2/?id=docs_gateway)是一种提供可调节计算容量的 Web 服务 – 简单来说，就是 Amazon 数据中心里的服务器 – 您可以使用它来构建和托管您的软件系统
            * [ECS](https://docs.aws.amazon.com/ecs/?id=docs_gateway)是一项高度可扩展的快速容器管理服务，可轻松运行、停止和管理 Amazon EC2 实例集群上的 Docker 容器
            * [lightsail](https://docs.aws.amazon.com/lightsail/?id=docs_gateway)仅需虚拟私有服务器的开发人员可以通过最简单的方式开始使用 AWS。Lightsail 包括您快速启动项目所需的一切 (虚拟机、基于 SSD 的存储、数据传输、DNS 管理和静态 IP)，价格低廉且可预测
            * [Elastic Beanstalk ](https://docs.aws.amazon.com/elastic-beanstalk/?id=docs_gateway)可让您迅速地在 AWS 云中部署和管理应用程序，而无需为运行这些应用程序的基础设施操心。AWS Elastic Beanstalk 可降低管理的复杂性，但不会影响选择或控制。您只需上传应用程序，AWS Elastic Beanstalk 将自动处理有关容量预配置、负载均衡、扩展和应用程序运行状况监控的部署细节
          * 基于容器的计算---可以让您更好地划分工作负载，并且可以快速扩展，但配置和编排更为复杂
          * 基于无服务器的计算---可消除大部分管理和扩展复杂性，但存在硬性系统限制，并且需要采用新的工具链和流程
        * 存储服务类别---存储是数据的静态存储（例如，对象存储）
          * 文件存储
            * [EFS](https://docs.aws.amazon.com/efs/?id=docs_gateway)为 Amazon EC2 实例提供文件存储。借助 Amazon EFS，您可以创建文件系统、将文件系统挂载到 EC2 实例上，然后读取来自 EC2 实例的数据并将其写入文件系统，反之亦然
          * 块存储
            * [EBS](https://docs.aws.amazon.com/ebs/?id=docs_gateway)是一种 Web 服务，可提供数据块级存储卷以用于 EC2 实例。EBS 卷是高度可用的可靠存储卷，可以挂载到任何正在运行的实例，并可像硬盘驱动器一样使用
          * 对象存储
            * [S3](https://docs.aws.amazon.com/s3/?id=docs_gateway)是一种面向 Internet 的存储服务。您可以通过 Amazon S3 随时在 Web 上的任何位置存储和检索的任意大小的数据。您可以使用 AWS 管理控制台简单而直观的 web 界面来完成这些任务
          * 存档存储
            * [S3 Glacier ](https://docs.aws.amazon.com/glacier/?id=docs_gateway)是一种针对不常用的数据（“冷数据”）而经过了优化的存储服务。 这项服务为数据存档和备份提供了持久且成本极低的存储解决方案及安全功能。使用 Amazon Glacier，您可以将数据经济高效地存储数月、数年，甚至数十年。Amazon Glacier 可让您将存储扩展到 AWS 并卸下操作以及管理负担，这样，您就不必担心容量规划、硬件配置、数据复制、硬件故障检测和恢复，或者耗时的硬件迁移等问题
        * 数据库服务类别---数据库是数据的有组织存储（例如，关系数据库）
          * 关系数据库---拥有联接和 ACID 属性，但性能和数据存储存在上限
            * [ACID](https://en.wikipedia.org/wiki/ACID)
            * [RDS](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Welcome.html)可以更好地控制底层数据库，并且可用于大多数关系数据库
            * [Aurora](https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/CHAP_AuroraOverview.html)仅适用于某些版本的 MySQL 和 PostgreSQL，但负责管理底层存储并内置集群支持
          * 非关系数据库---具有更灵活的架构，并且上限比关系数据库更高，但通常缺少联接和完整的 ACID 功能
            * [DynamoDB](https://docs.aws.amazon.com/dynamodb/?id=docs_gateway)是一种完全托管的 NoSQL 数据库服务，提供快速而可预测的性能，能够实现无缝扩展。您可以使用 Amazon DynamoDB 创建一个数据库表来存储和检索任何大小的数据，并处理任何级别的请求流量。Amazon DynamoDB 可自动将表的数据和流量分布到足够多的服务器中，以处理客户指定的请求容量和数据存储量，同时保持一致的性能和高效的访问。
          * 数据仓库解决方案---可以通过快速访问数 PB 的结构化数据，以实现大规模分析
            * [Redshift](https://docs.aws.amazon.com/redshift/?id=docs_gateway)是一种快速、完全托管的 PB 级数据仓库服务，它使得通过现有商业智能工具对您的所有数据进行高效分析变得简单而实惠。它为从几百 GB 到 1PB 或更大的数据集而优化，且每年每 TB 花费不到 1000 USD，为最传统数据仓库存储解决方案成本的十分之一
          * 数据索引和搜索---您可以索引和搜索来自各种来源的数据
            * [Elasticsearch Service ](https://docs.aws.amazon.com/elasticsearch-service/?id=docs_gateway)是一种托管服务，让用户能够轻松部署、运营和扩展 Elasticsearch (一种常见的开源搜索和分析引擎)。Amazon ES 还提供多种安全选项、高可用性、数据持久性以及对 Elasticsearch API 的直接访问权限
        * 网络服务类别---网络处理您的数据的移动（例如，内容交付网络）
      * 扩展
         * [Route 53 路由策略](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy.html)
         * [ALB 路由策略](https://aws.amazon.com/cn/blogs/aws/new-advanced-request-routing-for-aws-application-load-balancers/)
         * [Auto Scaling](https://docs.aws.amazon.com/autoscaling/?id=docs_gateway)AWS 提供多种服务，可用于扩展您的应用程序,Auto Scaling 由 Amazon CloudWatch 支持，除 CloudWatch 以及您使用的其他 AWS 资源的服务费外，不额外收取费用
         * [Route 53](https://docs.aws.amazon.com/route53/?id=docs_gateway)是一种可用性高、可扩展性强的域名系统 (DNS) Web 服务
         * [Elastic Load Balancer](https://docs.aws.amazon.com/elasticloadbalancing/?id=docs_gateway) 自动分配间应用程序的传入流量在多个目标， 如Amazon EC2 实例。它监控健康目标上的已注册目标和流量路的健康状况。Elastic Load Balancing 支持三种负载均衡器：应用程序负载均衡器、网络负载均衡器和 Classic 负载均衡器
  * 3. 可靠性
  * 4. 卓越运营
  * 5. 成本优化




# 视频
* [Build an Online book Store Using AWS on one day with React and Stripe ](https://www.youtube.com/watch?v=JgwI22y_eFA)
* [AWS for Startups - Deploying with AWS Tutorial](https://www.youtube.com/watch?v=U3VSJhaC4kc)
* [AWS Certified Cloud Practitioner Training 2020 - Full Course](https://www.youtube.com/watch?v=3hLmDS179YE&t=1s)
* [AWS SysOps Administrator Associate 2020 (PASS THE EXAM!)](https://www.youtube.com/watch?v=KX_AfyrhlgQ&t=106s)
* [AWS Certified Developer - Associate 2020 (PASS THE EXAM!)](https://www.youtube.com/watch?v=RrKRN9zRBWs&t=6s)
* [AWS Certified Solutions Architect - Associate 2020 (PASS THE EXAM!)](https://www.youtube.com/watch?v=Ia-UEYYR44s&t=907s)
* [AWS Certifications Roadmap for Everyone](https://www.youtube.com/watch?v=P2FKdqPbyk0)
* [ AWS Full Course - Learn AWS In 11 Hours](https://www.youtube.com/watch?v=cJLJrLlZ8no)
* [基於微服務與雲原生應用的持續交付實踐](https://www.youtube.com/watch?v=-noLaByJBDk)
* [AWS云计算证书及相关工作讲解](https://www.jiuzhang.com/seminar/153/)
* [AWS SysOps Administrator Associate 2020 (PASS THE EXAM!)](https://www.youtube.com/watch?v=KX_AfyrhlgQ)
# 有用的参考

## Amazon的参考
* [Spring官方文档： Spring Cloud AWS](https://cloud.spring.io/spring-cloud-aws/spring-cloud-aws.html#_basic_setup)
* [aws申请ec2实例后如何用root用户登录](https://www.cnblogs.com/yangzhaon/p/11969481.html)
* [AWS TECHNOLOGY SKILL PLATFORM CERTIFICATION](https://www.claydesk.com/)
* [ AWS 操作教程](https://aws.amazon.com/cn/getting-started/hands-on/?awsf.getting-started-content-type=*all&awsf.getting-started-category=*all)
* [云原生（Cloud Native）- 移动App研发新范式](https://www.douban.com/note/638744953/)
* [AWS Certified Developer - Associate 2020 (PASS THE EXAM!)](https://www.youtube.com/watch?v=RrKRN9zRBWs&t=3s)
* [部署SpringBoot项目到亚马逊aws云服务上](https://www.twblogs.net/a/5cb0c671bd9eee480f075dcf/?lang=zh-cn)
* [在AWS EC2上部署springboot项目](https://www.cnblogs.com/yelao/p/12589098.html)
* [Spring Cloud 微服务(五) 部署到AWS ECS](https://www.jianshu.com/p/1617d6948ee8)
* [AWS EC2 搭建 Hadoop 和 Spark 集群](https://www.cnblogs.com/massquantity/p/12088449.html)
* [AWS之EC2搭建WordPress博客](https://www.cnblogs.com/zhijian1574/p/11957133.html)
* [AWS之EC2实例搭建LAMP服务器](https://www.cnblogs.com/zhijian1574/p/11957128.html)
* [(导航页)Amazon Lightsail 部署LAMP应用程序(HA)](https://www.cnblogs.com/zhijian1574/p/11957172.html)
* [Deploy NodeJS APP on Amazon EC2 Instance](https://www.youtube.com/watch?v=tasoWTGM1hA)

## 阿里云的参考
* [使用GCP_EC2云服务器搭部署网络服务](https://www.cnblogs.com/zhijian1574/p/11957138.html)


