# Getting Started
![ALT TEXT](https://res.infoq.com/presentations/spring-rsocket/en/slides/sl8-1574781115040.jpg)
### Reference Documentation
For further reference, please consider the following sections:

* [Official Gradle documentation](https://docs.gradle.org)
* [Spring Boot Gradle Plugin Reference Guide](https://docs.spring.io/spring-boot/docs/3.1.1/gradle-plugin/reference/html/)
* [Create an OCI image](https://docs.spring.io/spring-boot/docs/3.1.1/gradle-plugin/reference/html/#build-image)
* [Spring Web](https://docs.spring.io/spring-boot/docs/3.1.1/reference/htmlsingle/#web)
* [RSocket](https://rsocket.io/)
* [Make a small project with rsocket in spring](https://www.baeldung.com/spring-boot-rsocket)
### Dive into RSocket in Spring
#### 1. Overview 
***RSocket is an application protocol providing Reactive Streams semantics - it functions, for example, as an alternative to HTTP***
- RSocket is a binary, symmetric protocol designed for reactive, asynchronous, and flow-controlled communication.
- It supports multiple transport protocols such as TCP, WebSocket, and more.
- RSocket provides features like request/response, streaming, request/channel (bidirectional streaming), and fire-and-forget.
- It is designed to be polyglot, meaning it can be used across different programming languages.
- RSocket is built to handle the challenges of microservices, IoT, and cloud-native architectures, where scalability, resilience, and efficient use of resources are crucial.
- It allows for backpressure, enabling the server to control the flow of data and prevent overload.
  RSocket has a Reactive Streams-based API and integrates well with reactive programming frameworks such as Spring WebFlux or Reactor.
### 2. Dependency in Spring
```xml
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-rsocket</artifactId>
</dependency>
```

