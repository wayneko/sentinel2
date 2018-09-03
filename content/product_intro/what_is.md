+++
title = "What is Sentinel"
date = 2018-08-27T11:44:02+08:00
weight = 5
+++

# What is Sentinel

The name should be Sentinel. Please mind the case.

## Overview

Welcome to Nacos!

Nacos is all things about discovery, configure and manage your microservices. Nacos provides users with a group of easy-to-use features set for dynamic service discovery, service configuration management, service and traffic management.

Nacos help users to build, deliver and manage their microservices platform more agile and easier. Nacos is a service infra when users build modern service centric applications by using microservices or cloud native approaches.

## What is Nacos？

Service is a first-class citizen in Nacos，Nacos support discovery，configure and manage almost all types of services such as，[Kubernetes Service](https://kubernetes.io/docs/concepts/services-networking/service/) , [gRPC](https://grpc.io/docs/guides/concepts.html#service-definition)[ | Dubbo RPC Service](https://dubbo.incubator.apache.org/#/?lang=en-us) or [Spring Cloud RESTful Service](https://spring.io/understanding/REST)

The key features of Nacos are:

* **Service Discovery And Service Health Check**

    Nacos supports both DNS-based and RPC-based (Dubbo/gRPC) service discovery, producer can register a service with [native sdk TODO](xx) or [OpenAPI TODO](xx) or by using [a dedicated agent TODO](xx), consumer can discovery this service with either [DNS TODO](xx) or [HTTP TODO](xx).

    Nacos also do real-time health check for services to prevent sending requests to unhealthy hosts, Nacos support either transport layer (ping or tcp) or application layer (http, redis, mysql, user-define) health check. For complex cloud environments and network topology(VPC, Edge Service etc), Nacos provides both agent mode or server mode health check. Nacos also provide a unity service health dashboard to help to manage the availability and traffic for services.    
    
* **Dynamic Configuration Management**

    Dynamic configuration service allows you to manage the configuration of all applications or services in a centralized, externalized and dynamic manner across all environments.

    Dynamic configuration eliminates the need to redeploy applications and services when configuring updates.

    It can be more convenient to help you achieve stateless services and more easily elastic expansion of service instances on-demand.

    Naocs provide an [easy-to-use UI TODO](xx) to help you management all of your configurations and provide some out-of-box features such as config version track, canary release and rollback config, client configuration update status tracking etc.

* **Dynamic DNS Service**

    Dynamic DNS services that support weighted routing make it easier for you to implement mid-tier load balancing, flexible routing policies, traffic control, and simple DNS resolution services in your production environment within your data center, helping you to more easily implement DNS-based Service discovery. Nacos provide some simple [DNS APIs TODO](xx) for managing your DNS domain name and IPs.

* **Service Governance and MetaData Management**

   Nacos support manage all for your services and their metadata from the perspective of building the microservices platform. This includes manage the service description, life cycle, static dependencies analysis, service health status, service traffic management，routing and security rules, service SLA and first line metrics et al.

* [Check More Features ...](xx)

## Nacos Landscape

![nacos_landscape.png](https://cdn.yuque.com/lark/0/2018/png/15914/1530514380550-31251a79-02bb-4155-bc4f-5a9f436551a2.png) 

As the above Nacos landscape shows, Nacos seamless support many open source encology,such as [Dubbo and Dubbo Mesh](xx), [Spring Cloud](xx)， [Kubernetes and CNCF](xx).

With Nacos, you can take the advantage of various aspects of Nacos's capabilities to simplify your solutions in service discovery, configuration management, service governance and management, Nacos help to manage your micro-services on these platforms more easier.

For how touse Nacos with other open source products, check following docs :

[Use Nacos with Kubernetes](xx)
[Use Nacos with Dubbo](xx)
[Use Nacos with gRPC](xx)
[Use Nacos with Spring Cloud](xx)
[Use Nacos with lstio](xx)


## What’s next

Continue onwards with [quick start](xxx) to get Nacos up and running.


