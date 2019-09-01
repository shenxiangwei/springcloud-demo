# springcloud-demo
spingcloud demo依赖于SpringBoot实现,eureka服务注册中心

1.启动EurekaServerApplication，访问http://localhost:8761/

2.启动EurekaClientApplication，访问http://localhost:9000/service-instances/eureka-client 返回实例信息，如下

[
    {
        "host":"host.docker.internal",
        "port":9000,
        "metadata":{
            "management.port":"9000"
        },
        "secure":false,
        "uri":"http://host.docker.internal:9000",
        "instanceId":"host.docker.internal:eureka-client:9000",
        "serviceId":"EUREKA-CLIENT",
        "instanceInfo":{
            "instanceId":"host.docker.internal:eureka-client:9000",
            "app":"EUREKA-CLIENT",
            "appGroupName":null,
            "ipAddr":"192.168.0.106",
            "sid":"na",
            "homePageUrl":"http://host.docker.internal:9000/",
            "statusPageUrl":"http://host.docker.internal:9000/actuator/info",
            "healthCheckUrl":"http://host.docker.internal:9000/actuator/health",
            "secureHealthCheckUrl":null,
            "vipAddress":"eureka-client",
            "secureVipAddress":"eureka-client",
            "countryId":1,
            "dataCenterInfo":{
                "@class":"com.netflix.appinfo.InstanceInfo$DefaultDataCenterInfo",
                "name":"MyOwn"
            },
            "hostName":"host.docker.internal",
            "status":"UP",
            "overriddenStatus":"UNKNOWN",
            "leaseInfo":{
                "renewalIntervalInSecs":30,
                "durationInSecs":90,
                "registrationTimestamp":1567328692390,
                "lastRenewalTimestamp":1567328841752,
                "evictionTimestamp":0,
                "serviceUpTimestamp":1567328691796
            },
            "isCoordinatingDiscoveryServer":false,
            "metadata":{
                "management.port":"9000"
            },
            "lastUpdatedTimestamp":1567328692391,
            "lastDirtyTimestamp":1567328691742,
            "actionType":"ADDED",
            "asgName":null
        },
        "scheme":null
    }
]
