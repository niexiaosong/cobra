
## Spring Cloud framework  - server-center

_服务中心项目基于Spring Boot 1.5.2.RELEASE，Spring Cloud Dalston.RELEASE，各模块简要说明如下

| project | desc |  
| --- | --- |  
 
| [eureka-server](eureka-server/README.md) | Eureka Server 服务注册中心 |  
| [eureka-server-ha](eureka-server-ha/README.md) | Eureka Server 双节点集群 |  
| [zuul-gateway](zuul-gateway/README.md) | Zuul 服务网关，依赖 eureka-server-ha，可配合 eureka-client  使用  |  
| [eureka-client](eureka-client/README.md) | Eureka客户端，依赖 eureka-server-ha |  

