
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
  * 1. 安全性
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
      * [Amazon Virtual Private Cloud (VPC)](https://aws.amazon.com/cn/vpc/)
      * [Application Load Balancer (ALB) ](https://docs.aws.amazon.com/elasticloadbalancing/latest/application/introduction.html)
      * [AWS Web 应用程序防火墙 (WAF)](https://aws.amazon.com/cn/waf/)
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
      * 选择
        * 计算---计算是处理数据的服务（例如，虚拟机）
          * 基于VM的计算---是大多数人最熟悉的思维模式，但价格可能更高，并且需要更多维护
          * 基于容器的计算---可以让您更好地划分工作负载，并且可以快速扩展，但配置和编排更为复杂
          * 基于无服务器的计算---可消除大部分管理和扩展复杂性，但存在硬性系统限制，并且需要采用新的工具链和流程
        * 存储---存储是数据的静态存储（例如，对象存储）
          * 文件存储
          * 块存储
            * [EBS](https://docs.aws.amazon.com/ebs/?id=docs_gateway)这样的块存储服务非常适合持久存储来自单个 EC2 实例的数据
            * 
          * 对象存储
          * 存档存储
        * 数据库---数据库是数据的有组织存储（例如，关系数据库）
        * 网络---网络处理您的数据的移动（例如，内容交付网络）
      * 扩展
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


