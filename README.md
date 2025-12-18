# SmartLearn
该项目实现了由机构端在登录认证后，完成课程上传与发布，运营端人员完成对课程的审核，最后由用户端完成登录校验，选课学习，支付宝完成支付交易等。
确保以下工具已安装：

JDK 17（或 8/11，看版本要求）
Maven 3.8+
MySQL 8.0
Redis 6+
Elasticsearch 7.17 + IK 分词器
Nacos 2.2+（服务注册与配置中心）
MinIO（对象存储，替代阿里 OSS）
RabbitMQ / Kafka（可选，部分功能依赖）
