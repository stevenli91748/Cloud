
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
  * 2 性能效率
      * [2.1 实例存储](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/InstanceStorage.html)
      * [2.2 已预置的容量](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/HowItWorks.ReadWriteCapacityMode.html)
      * [2.3 IOPS](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ebs-io-characteristics.html)
      * [2.4 AWS Lambda](https://docs.aws.amazon.com/lambda/?id=docs_gateway)
      * 2.5 选择
        * 2.5.1 计算服务类别---计算是处理数据的服务（例如，虚拟机）
          * 基于VM的计算---是大多数人最熟悉的思维模式，但价格可能更高，并且需要更多维护
            * [EC2](https://docs.aws.amazon.com/ec2/?id=docs_gateway)是一种提供可调节计算容量的 Web 服务 – 简单来说，就是 Amazon 数据中心里的服务器 – 您可以使用它来构建和托管您的软件系统
            * [ECS](https://docs.aws.amazon.com/ecs/?id=docs_gateway)是一项高度可扩展的快速容器管理服务，可轻松运行、停止和管理 Amazon EC2 实例集群上的 Docker 容器
            * [lightsail](https://docs.aws.amazon.com/lightsail/?id=docs_gateway)仅需虚拟私有服务器的开发人员可以通过最简单的方式开始使用 AWS。Lightsail 包括您快速启动项目所需的一切 (虚拟机、基于 SSD 的存储、数据传输、DNS 管理和静态 IP)，价格低廉且可预测
            * [Elastic Beanstalk ](https://docs.aws.amazon.com/elastic-beanstalk/?id=docs_gateway)可让您迅速地在 AWS 云中部署和管理应用程序，而无需为运行这些应用程序的基础设施操心。AWS Elastic Beanstalk 可降低管理的复杂性，但不会影响选择或控制。您只需上传应用程序，AWS Elastic Beanstalk 将自动处理有关容量预配置、负载均衡、扩展和应用程序运行状况监控的部署细节
          * 基于容器的计算---可以让您更好地划分工作负载，并且可以快速扩展，但配置和编排更为复杂
          * 基于无服务器的计算---可消除大部分管理和扩展复杂性，但存在硬性系统限制，并且需要采用新的工具链和流程
        * 2.5.2 存储服务类别---存储是数据的静态存储（例如，对象存储）
          * 文件存储
            * [EFS](https://docs.aws.amazon.com/efs/?id=docs_gateway)为 Amazon EC2 实例提供文件存储。借助 Amazon EFS，您可以创建文件系统、将文件系统挂载到 EC2 实例上，然后读取来自 EC2 实例的数据并将其写入文件系统，反之亦然
          * 块存储
            * [EBS](https://docs.aws.amazon.com/ebs/?id=docs_gateway)是一种 Web 服务，可提供数据块级存储卷以用于 EC2 实例。EBS 卷是高度可用的可靠存储卷，可以挂载到任何正在运行的实例，并可像硬盘驱动器一样使用
          * 对象存储
            * [S3](https://docs.aws.amazon.com/s3/?id=docs_gateway)是一种面向 Internet 的存储服务。您可以通过 Amazon S3 随时在 Web 上的任何位置存储和检索的任意大小的数据。您可以使用 AWS 管理控制台简单而直观的 web 界面来完成这些任务
          * 存档存储
            * [S3 Glacier ](https://docs.aws.amazon.com/glacier/?id=docs_gateway)是一种针对不常用的数据（“冷数据”）而经过了优化的存储服务。 这项服务为数据存档和备份提供了持久且成本极低的存储解决方案及安全功能。使用 Amazon Glacier，您可以将数据经济高效地存储数月、数年，甚至数十年。Amazon Glacier 可让您将存储扩展到 AWS 并卸下操作以及管理负担，这样，您就不必担心容量规划、硬件配置、数据复制、硬件故障检测和恢复，或者耗时的硬件迁移等问题
        * 2.5.3 数据库服务类别---数据库是数据的有组织存储（例如，关系数据库）
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
        * 2.5.4 网络服务类别---网络处理您的数据的移动（例如，内容交付网络）
      * 2.6 扩展
         * [2.6.1 Route 53 路由策略](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy.html)
         * [2.6.2 ALB 路由策略](https://aws.amazon.com/cn/blogs/aws/new-advanced-request-routing-for-aws-application-load-balancers/)
         * [2.6.3 Auto Scaling](https://docs.aws.amazon.com/autoscaling/?id=docs_gateway)AWS 提供多种服务，可用于扩展您的应用程序,Auto Scaling 由 Amazon CloudWatch 支持，除 CloudWatch 以及您使用的其他 AWS 资源的服务费外，不额外收取费用
         * [2.6.4 Route 53](https://docs.aws.amazon.com/route53/?id=docs_gateway)是一种可用性高、可扩展性强的域名系统 (DNS) Web 服务
         * [2.6.5 Elastic Load Balancer](https://docs.aws.amazon.com/elasticloadbalancing/?id=docs_gateway) 自动分配间应用程序的传入流量在多个目标， 如Amazon EC2 实例。它监控健康目标上的已注册目标和流量路的健康状况。Elastic Load Balancing 支持三种负载均衡器：应用程序负载均衡器、网络负载均衡器和 Classic 负载均衡器
  * 3 可靠性
    * 三个级别的故障隔离区
      * [AWS re:Invent 2018：AWS 如何最大程度地降低故障的影响半径](https://www.youtube.com/watch?v=swQbA4zub20)
      * [资源和请求级别的故障隔离区]()AWS 服务根据给定维度（如资源 ID）对所有资源和请求进行分区。这些分区称为单元。单元被设计为独立存在，并在将故障限制在自身范围内。在背后，AWS 利用随机分区之类的技术来限制影响半径。每次您提出请求或创建资源时，所有这些都会以透明的方式发生，并且您不需要任何其他操作。
        * [随机分区](https://aws.amazon.com/cn/builders-library/workload-isolation-using-shuffle-sharding/?did=ba_card&trk=ba_card#What_is_shuffle_sharding.3F)
      * [用用区级别的故障隔离区]()AWS 可用区 (AZ) 是完全独立的设施，具有专用的电源、服务和网络功能。可用区彼此之间在地理上相距较远，以免因火灾和洪水等环境危害而出现相关故障。通过在多个可用区中部署服务的冗余实例，可以在可用区级别实现故障隔离。这样做意味着一个可用区中的电源事件不会影响您在另一个可用区中的流量。关于延迟，尽管 AZ 在地理位置上是有距离的，但彼此之间的距离足够近，以至于 AZ 之间的网络延迟很小。这使得某些功能（如同步数据复制）可以在可用区之间实现。
      * [区域级别的故障隔离区]()AWS 区域提供了最极致的隔离方式。每个区域都是一个完全自治的数据中心，由两个或多个可用区组成。通过在不同的 AWS 区域之间部署服务的冗余副本，可以在区域级别实现故障隔离（这正是 AWS 在自己的服务上所使用的方式）。如果您需要非常高的可用性，可考虑部署到多个区域。请注意，由于区域之间没有共享的基础设施，因此跨多个区域运行服务会产生大量开销。有一些服务和功能可以帮助您进行多区域构建。例如，您可以使用 AWS 的可扩展 DNS 服务 Route53 在不同区域之间路由流量。您还可以使用 DynamoDB 全局表和 S3 跨区域复制之类的功能来跨区域复制数据
        * [DynamoDB 全局表](https://aws.amazon.com/cn/dynamodb/global-tables/)全局表基于 Amazon DynamoDB 的全球覆盖范围构建，为您提供一个完全托管的多区域、多主控数据库，该数据库为大规模的全局应用程序提供快速的本地读写性能。全局表会在您选择的 AWS 区域中自动复制您的 DynamoDB 表
        * [S3 跨区域复制](https://docs.aws.amazon.com/AmazonS3/latest/dev/replication.html)
        * [Route53](https://docs.aws.amazon.com/route53/?id=docs_gateway)是一种可用性高、可扩展性强的域名系统 (DNS) Web 服务
    * 限制的两种类型
      * 可以通过向 AWS 请求提高上限的软限制
        * [Service Quotas](https://docs.aws.amazon.com/servicequotas/?id=docs_gateway) is a service for viewing and managing your quotas easily and at scale as your AWS workloads grow. Quotas, also referred to as limits, are the maximum number of resources that you can create in an AWS account.
          * [所有 AWS Service Quotas](https://docs.aws.amazon.com/general/latest/gr/aws-service-information.html)
        * [AWS Trusted Advisor](https://aws.amazon.com/cn/premiumsupport/technology/trusted-advisor/)降低成本、提高性能并改善安全性
        * [并行 Lambda 执行](https://docs.aws.amazon.com/lambda/latest/dg/configuration-concurrency.html)
        * [Amazon CloudWatch](https://docs.aws.amazon.com/cloudwatch/?id=docs_gateway)提供可靠、可调整且灵活的监测解决方案，让您可在短短几分钟内开始使用。您不再需要设置、管理和扩展监控系统和基础设施了
        * [使用 Trusted Advisor 和 Amazon CloudWatch 监控服务限制](https://aws.amazon.com/cn/blogs/mt/monitoring-service-limits-with-trusted-advisor-and-amazon-cloudwatch/)
        * [awslimitchecker](https://github.com/jantman/awslimitchecker)
      * 不能提高上限的硬限制
  * 4 卓越运营
    * 基础设施即代码
      * [基础设施即代码 (IaC) ](https://en.wikipedia.org/wiki/Infrastructure_as_code)是通过计算机可读配置文件管理基础设施的过程。IaC 是实现基础设施自动化的基础。您无需创建手动预置服务，而是创建描述所需资源的模板。然后，IaC 平台将代您预置和配置资源。IaC 为您提供了一种声明式的自动预置基础设施的方式。它使您可以像对待代码一样对待基础设施，使用相同的工具（例如，git）和流程（例如，代码审查）。传统上，我们使用 CloudFormation 服务在 AWS 上实现 IaC。CloudFormation 需要使用 JSON 或 YAML 声明您的资源。如果您不喜欢这些配置语言，AWS 还提供了 Cloud Development Kit (CDK)，让您可以使用 JavaScript、Python 和 Java 等本机编程语言来编写 CloudFormation 模板
      * [ CloudFormation](https://docs.aws.amazon.com/cloudformation/?id=docs_gateway)借助 AWS CloudFormation，您可以有预见性地、重复地创建和预置 AWS 基础设施部署。它可以帮助您利用 AWS 产品 (如 Amazon EC2、Amazon Elastic Block Store、Amazon SNS、Elastic Load Balancing 和 Auto Scaling) 在云中构建高度可靠、高度可扩展且经济高效的应用程序，为您免除创建和配置底层 AWS 基础设施之忧。借助 AWS CloudFormation，您可以使用模板文件，将资源集作为一个单元 (堆栈) 进行创建和删除
        * [CloudFormation 属性参考](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/aws-template-resource-type-ref.html)
      * [Cloud Development Kit (CDK)](https://docs.aws.amazon.com/cdk/?id=docs_gateway)is a software development framework for defining your cloud infrastructure in code and provisioning it through AWS CloudFormation
        * [CDK API 参考](https://docs.aws.amazon.com/cdk/api/latest/docs/aws-construct-library.html)
    * [可观测性三步]()可观测性是衡量系统内部状态的过程。通常这样做是为了将其优化到某个所需的最终状态.要实现卓越运营，您需要改进系统，而改善系统则要求您能够衡量系统。建立坚实的可观测性基础使您能够跟踪自动化的影响，并不断进行改进
      * 收集---收集是在评估系统状态时汇总所有必要指标的过程
        * 基础设施级指标---这些指标由 AWS 服务自动发出，并由 CloudWatch 服务收集某些服务还会发出可通过 CloudWatch Logs 启用和收集的结构化日志
          * [CloudWatch ](https://docs.aws.amazon.com/cloudwatch/?id=docs_gateway)提供可靠、可调整且灵活的监测解决方案，让您可在短短几分钟内开始使用。您不再需要设置、管理和扩展监控系统和基础设施了
          * [CloudWatch Logs ](https://docs.aws.amazon.com/AmazonCloudWatch/latest/logs/WhatIsCloudWatchLogs.html)
        * 应用程序级指标---这些指标由您的软件生成，可以由 CloudWatch 自定义指标 收集,可以使用 CloudWatch Logs 存储软件日志或将其上传到 S3
          * [CloudWatch 自定义指标 ](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/publishingMetrics.html)
        * 账户级指标---这些指标由您的 AWS 账户记录，可以由 CloudTrail 服务收集
          * [AWS CloudTrail](https://docs.aws.amazon.com/cloudtrail/?id=docs_gateway)
      * 分析---要分析收集的指标，您可以使用 AWS 提供的众多数据库和分析解决方案之一
        * [AWS 分析服务概述](https://docs.aws.amazon.com/whitepapers/latest/aws-overview/analytics.html)
        * 要分析存储在 CloudWatch Logs 中的日志，可考虑使用 CloudWatch Logs Insight，该服务可让您交互式地搜索和分析 Cloudwatch 日志数据
          * [CloudWatch Logs Insight](https://docs.aws.amazon.com/AmazonCloudWatch/latest/logs/AnalyzingLogData.html)
        * 要分析存储在 S3 中的日志，可考虑使用 Athena（一种无服务器查询服务）
          * [Athena](https://aws.amazon.com/cn/athena/?id=docs_gateway&whats-new-cards.sort-by=item.additionalFields.postDateTime&whats-new-cards.sort-order=desc) 是一种交互式查询服务，让您能够轻松使用标准 SQL 分析 Amazon S3 中的数据。Athena 没有服务器，因此您无需管理任何基础设施，且只需为您运行的查询付费
        * 要分析结构化数据，可考虑使用 RDS（一种托管的关系数据库服务）
          * [RDS](https://docs.aws.amazon.com/rds/?id=docs_gateway)是一种 Web 服务，可让用户更轻松地在云中设置、操作和扩展关系数据库。它可以经济有效的为用户提供一个容量可调的行业标准的关系数据库，并承担常见的数据库管理任务
        * 要分析大量结构化数据，可考虑使用 RedShift（一种托管的 PB 级数据仓库服务）
          * [RedShift](https://docs.aws.amazon.com/redshift/?id=docs_gateway)是一种快速、完全托管的 PB 级数据仓库服务，它使得通过现有商业智能工具对您的所有数据进行高效分析变得简单而实惠。它为从几百 GB 到 1PB 或更大的数据集而优化，且每年每 TB 花费不到 1000 USD，为最传统数据仓库存储解决方案成本的十分之一
        * 要分析基于日志的数据，可考虑使用 Elasticsearch Service，这是流行的开源分析引擎 Elasticsearch 的托管版本
          * [Elasticsearch Service](https://docs.aws.amazon.com/elasticsearch-service/?id=docs_gateway) 是一种托管服务，让用户能够轻松部署、运营和扩展 Elasticsearch (一种常见的开源搜索和分析引擎)。Amazon ES 还提供多种安全选项、高可用性、数据持久性以及对 Elasticsearch API 的直接访问权限
      * 行动---在收集并分析了指标之后，可以使用它们来实现特定的结果或流程
        * [监控与警报]()您可以使用 CloudWatch Alarms 在系统超出特定指标的安全阈值时获得通知,此警报可以触发手动或自动缓解措施
          * [CloudWatch Alarms ](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/AlarmThatSendsEmail.html)
          * [AWS X-Ray 文档](https://docs.aws.amazon.com/xray/?id=docs_gateway)提供请求跟踪、异常收集以及分析功能，使开发人员能够轻松分析分布式应用程序的行为
        * [控制面板]()您可以使用 Cloudwatch 控制面板创建指标的控制面板,您可以使用这些控制面板跟踪和改善服务性能
          * [Cloudwatch 控制面板](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/CloudWatch_Dashboards.html)
        * [数据驱动型决策]()
  * 5 成本优化
      * 按使用量付费
        * [合理调整大小]()合理调整大小是指让服务预置和配置与工作负载相匹配。对于基于 EC2 的服务，这意味着选择正确的实例大小和系列。如果您的计算资源大部分闲置，请考虑使用较小的 EC2 实例。如果您的工作负载需要大量特定的系统资源，请考虑转用针对该资源优化的实例系列
          * [AWS Compute Optimizer](https://aws.amazon.com/cn/compute-optimizer/)为您的工作负载建议最佳的 AWS 计算资源，以通过使用机器学习分析历史利用率指标来降低成本并提高性能
          * [合理调整大小](https://aws.amazon.com/cn/aws-cost-management/aws-cost-optimization/right-sizing/)Provisioning Instances to Match Workloads
        * [无服务器]()当您使用 Lambda 之类的无服务器技术时，只需为使用的部分付费。如果您的 Lambda 没有执行，则不会向您收费。无服务器是按使用量付费的最鲜明例子。在用例允许的情况下，选择无服务器可能是构建服务最具成本效益的方式
        * [预留]()请求预留意味着承诺支付一定容量的费用以换取大幅折扣
          * [ Savings Plans](https://aws.amazon.com/cn/getting-started/fundamentals-core-concepts/?e=gs2020&p=fundoverview)是一种灵活的定价模式，最高可节省 72% 的 AWS 计算使用费
          * [Amazon RDS 预留实例](https://aws.amazon.com/cn/rds/reserved-instances/)
          * [DynamoDB 预置容量](https://aws.amazon.com/cn/dynamodb/pricing/provisioned/)
        * [Spot 实例]()使您可以利用未使用的 EC2 容量，最多可以以比按需价格少 90% 的折扣价格运行实例。这可以为您的容错工作负载节省大量资金
          * [EC2 Spot 实例](https://aws.amazon.com/cn/ec2/spot/?cards.sort-by=item.additionalFields.startDateTime&cards.sort-order=asc)Amazon EC2 Spot 实例让您可以利用 AWS 云中未使用的 EC2 容量。与按需实例的价格相比，使用 Spot 实例最高可以享受 90% 的折扣
      * 成本优化生命周期
        * 查看
          * [AWS Cost Explorer ](https://aws.amazon.com/cn/aws-cost-management/aws-cost-explorer/)可帮助您直观地了解一段时间内的云支出。您可以按服务和类别等不同方面细分支出。使用 Cost Explorer 可以获取有关帐单的概述和详细报告
          * [AWS 成本和使用情况报告](https://aws.amazon.com/cn/aws-cost-management/aws-cost-and-usage-reporting/)深入了解您的 AWS 成本和使用情况,可以自定义 AWS 成本和使用情况报告，以将您的使用情况数据汇总到每小时、每天或每月级别
        * 跟踪
          * [成本分配标签](https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/cost-alloc-tags.html)可以按照您关注的维度对其进行分组。您可以使用成本分配标签完成此操作。需要为每个要跟踪的标签打开这些
          * [AWS 预算](https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/budgets-managing-costs.html)创建预算目标。使用预算，您可以监控自己关注的各个维度上的支出
        * 优化
          * [AWS 成本优化资源中心](https://aws.amazon.com/cn/aws-cost-management/)




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


