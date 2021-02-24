 <center>
     <h1>许俊鹏</h1>
     <div>
         <span>
             <img src="assets/phone-solid.svg" width="18px">
             13439794480
             &emsp;&emsp;
         </span>
         <span>
             <img src="assets/envelope-solid.svg" width="18px">
             weakeexu@gmail.com
             &emsp;&emsp;
         </span>
         <span>
             <img src="assets/graduation-cap-solid.svg" width="18px">
             郑州轻工业大学-软件工程
              &emsp;&emsp;
         </span>
     </div>
 </center>

 ## <img src="assets/info-circle-solid.svg" width="30px"> 个人信息 

 - 男 1995年出生
 - 求职意向：系统研发,python, java, go
 - 工作经验：3年
 - 期望薪资：30k


## <img src="assets/briefcase-solid.svg" width="30px"> 工作经历

- **北京陌陌科技有限公司，大数据部门，系统研发工程师，2019.11~至今**

   负责大数据部机器学习平台研发，旧系统的维护, 技术改造接入公司内部工具


- **北京完美创意科技有限公司，技术部，后台开发工程师，2018.6~2019.11**

   负责社区端业务开发，负责主站功能开发


- **北京星尘纪元科技有限公司，技术部，实习，2018.2～2018.6**

   负责标注平台维护，对接运营部门提供数据支持

## <img src="assets/project-diagram-solid.svg" width="30px"> 项目经历

- **陌陌机器学习平台**

  *使用到的技术:  python, java, golang, vue, mysql, kafka, redis*

    - 主要使用语言为python， 建立通用化机器学习平台, 对公司内部提供算法解决方案, 主要承接公司全部审核检测，内容安全相关业务，提高算法模型对外提供服务的效率。实现了算法人员只需要提供模型及相关与阈值配置，既可快速承接业务。并完善部分脚本，支持快速在容器中横向部署。通过结合模型管理服务，实现模型热更新，不需发布既可完成新模型上线
    - 使用vue+flask实现可视化平台(组内使用), 通过开源vue-admin-template框架实现前端页面，使用python的flask框架搭建后端服务。mysql，redis用作后端存储。使用这些技术快速搭建出一个可视化平台，替代了部分脚本操作，以及配置的管理。后端架构为mcv结构，实现了较为通用的后台管理系统。
    - 使用python+go实现限流与降级方案，go为server端, 主要封装了令牌桶算法, 通过协程与单利, 实现令牌的分发, 充分利用服务器资源。 python为client端, 向服务端请求令牌，同时实现了本地限流作为降级方案。
    - 使用java开发数据中转服务, 应对了python3对kafka的部分支持不友好的场景，同时配合redis，避免了kafka消费者数量与分片数量的绑定关系
    - 根据对已有业务的整理，抽象出公共部分, 通过配置文件的方式来取代重复代码，实现了不同的业务根据不同的配置文件即可完成快速部署。
    - 调研新技术, 根据实际需要引入到机器学习平台, 调研了pika， 利用pika高吞吐特性，用于模型处理过程中中间结果的保存, 调研了zipkin用做整个平台的链路追踪, 接入
sentry用作服务异常情况的监控



- **更美app**

  *使用到的技术:  python, django, mysql, es, celery*
    
    - 负责社区端需求开发，主要负责主站首页各种活动入口展示以及相关的功能实现
    - 负责针对首页的性能优化，利用mysql索引优化，表结构优化，以及适当的redis缓存提高服务响应速度，部分接口实现并行化，首页响应速度提升了50%。并制定了降级方案，通过feed推荐来补充部分数据在一场情况下不能展示的问题
    - 负责app面部扫描功能，调研市场中的人脸识别服务商，根据产品需要进行选择，与各方对接并设计详细开发方案，满足了在快速迭代的过程中高效提供支持以及高扩展性
    - 负责运营后台的开发，根据实际需要，对公司内部自研框架进行二次开发
    - 配合测试人员对主站主要接口进行压力测试


- **星尘标注后台**

    主要使用语言为python, flask, mysql, mongo, redis 做存储
    
    - 参与标注平台的开发与维护
    - 参与单元测试
    - 实现服务容器化


## <img src="assets/tools-solid.svg" width="30px"> 技能清单

- ★★★ Python 
- ★★☆ MySQL、Redis、Kafka、ES
- ★☆☆ Golang、Vue、使用pytorch训练分类模型
