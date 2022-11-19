# currency-exchange-microservices
Some notes while going over the course: 

API Gateway-API Gateway **acts as a "front door" for applications to access data, business logic, or functionality from your backend services**

Naming Server-**helping to connect your domain name with the IP address of your web server**

Rabbit MQ-It gives your applications a common platform to send and receive messages, and your messages a safe place to live until received.

Currency-exchange-service

Currency-conversion-service

OpenZipkin for Distributed Tracing (helps gather timing data needed to troubleshoot latency problems in service architectures)
Feign is used as a load balancer between multiple applications.
Eureka is used for a naming server to name the multiple applications
Using a framework in springboot called sleuth, we are able to put a unique id on the request that could go across multiple microservices so we are able to track the response that gets sent back. 
Circuit breaker basically allows a microservice to return a fallback response if the microservice that this current microservice is dependent on is slow or down. It helps reduce load.

## Google Cloud: Kubernetes Cluster, Microservices, Docker Images🙈 :


<table>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/50753562/198386399-df008d87-fea5-4871-a0f7-ced36aafba08.png" alt="home" /></td>
  </tr>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/50753562/198386403-da483afc-bcc3-4a67-8e44-d64c6f33c179.png" alt="products" /></td>
  </tr>
  <tr>
    <td><img src="https://user-images.githubusercontent.com/50753562/198386409-677ea657-bcf2-4d99-a2f8-f75972754512.png" /></td>
  </tr>
</table>

