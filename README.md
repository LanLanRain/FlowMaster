## PmHub: Intelligent Project Management System

**PmHub** is an intelligent project management system built on **SpringCloud** and **Large Language Models (LLM)**. This project aims to provide a comprehensive learning experience for developers interested in mastering microservices and distributed systems architecture.

### Project Highlights

- **Cutting-edge Technologies**: Utilizes popular frameworks like SpringCloud Gateway, Nacos, and Sentinel, making it highly relevant to real-world enterprise projects.
- **Monolithic and Microservices Versions**: Offers both monolithic and microservices versions, catering to beginners and advanced learners, and demonstrates the full migration process from monolithic to microservices architecture.
- **Real Interview Scenarios**: Provides real interview scenarios and questions based on actual experiences, along with 1-on-1 resume review services.
- **High Code Quality**: Developed by an expert with experience at Ant Financial, following best practices to help developers maintain clean code.
- **Continuous Integration and Deployment**: Includes comprehensive CI/CD configurations using Docker to simulate a production environment.
- **Product Design Documentation**: Offers full product design documentation, including requirements, architecture, and prototypes, which are essential skills in a real-world workplace.
- **Enterprise Workflow System**: An open-source enterprise workflow system that can be customized for your company's needs, saving significant development costs.

### 1. Project Overview

**PmHub** consists of multiple services like authentication, workflow, project management, user management, and gateway services. It incorporates popular technologies such as:

- Redis, RocketMQ, Docker, Jenkins, Spring Security, Nacos, Sentinel, Seata, Spring Boot Actuator, SkyWalking, OpenFeign, and Vue3.

This project is also a development framework for enterprise workflows, allowing for quick customization based on specific business needs.

### 2. Technical Architecture

**PmHub** follows a microservices architecture, with a layered structure that includes front-end, gateway, service applications, and core service components like caching, messaging, monitoring, and distributed transaction management.

![System Architecture](https://cdn.tobebetterjavaer.com/stutymore/01.什么是PmHub-20240708113736.png)

### 3. Code Structure

```
com.lb.pmhub     
├── pmhub-ui              // Frontend Framework
├── pmhub-gateway         // Gateway Module
├── pmhub-auth            // Authentication Center
├── pmhub-api             // API Modules
│       └── pmhub-api-system        // System API
│       └── pmhub-api-workflow      // Workflow API
├── pmhub-base            // Core Modules
│       └── pmhub-base-core         // Core Components
│       └── pmhub-base-datasource   // Data Source Components
│       └── pmhub-base-seata        // Distributed Transaction Components
│       └── pmhub-base-security     // Security Components
│       └── pmhub-base-swagger      // Swagger Integration
│       └── pmhub-base-notice       // Messaging Components
├── pmhub-modules         // Business Modules
│       └── pmhub-system            // System Module
│       └── pmhub-gen               // Code Generation Module
│       └── pmhub-job               // Scheduled Tasks
│       └── pmhub-project           // Project Management
│       └── pmhub-workflow          // Workflow Management
├── pmhub-monitor         // Monitoring Center
└── pom.xml               // Common Dependencies
```

### 4. Deployment Instructions

#### 4.1 Prerequisites

| No | Technology             | Name            | Version     | Official Site |
|----|------------------------|-----------------|-------------|---------------|
| 1  | Spring Boot            | Framework       | 2.7.18      | [Spring Boot](https://spring.io/projects/spring-boot) |
| 2  | SpringCloud            | Microservice Framework | 2021.0.8 | [Spring Cloud](https://spring.io/projects/spring-cloud) |
| 3  | SpringCloud Alibaba    | Alibaba's Microservice Framework | 2021.0.5.0 | [SpringCloud Alibaba](https://github.com/alibaba/spring-cloud-alibaba) |
| 4  | MyBatis-Plus           | ORM Framework   | 3.5.1       | [MyBatis-Plus](https://baomidou.com) |
| 5  | Redis                  | Distributed Cache | Latest  | [Redis](https://redis.io) |
| 6  | RocketMQ               | Message Queue   | 2.2.3       | [RocketMQ](https://rocketmq.apache.org) |
| 7  | HuTool                 | Utility Toolkit | 5.8.11      | [HuTool](https://hutool.cn) |
| 8  | Maven                  | Build Tool      | 3.9.1       | [Maven](http://maven.apache.org) |
| 9  | Sentinel               | Flow Control    | 1.8.6       | [Sentinel](https://github.com/alibaba/Sentinel) |
| 10 | Java                   | Development Version | 1.8   | [Java](https://www.oracle.com/java/technologies) |
