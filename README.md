# Currency-Exchange Microservices project from Course

<br />
<p align="center">
    <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white" alt="java" />
    <img src="https://img.shields.io/badge/Rest_API-02303A?style=for-the-badge&logo=react-router&logoColor=white" alt="restAPI"/>
    <img src="https://img.shields.io/badge/Docker-1572B6?style=for-the-badge&logo=docker&logoColor=white" alt="docker" />
    <img src="https://img.shields.io/badge/Kubernetes-E34F26?style=for-the-badge&logo=kubernetes&logoColor=white" alt="kubernetes"/>
    <img src="" alt="" />
</p>
## Learn with me
### Some notes while going over the course: 

### [What is an API gateway? ](https://www.redhat.com/en/topics/api/what-does-an-api-gateway-do#:~:text=An%20API%20gateway%20is%20an,and%20return%20the%20appropriate%20result.)

### [What is a naming server? ](https://support.dnsimple.com/articles/what-is-a-nameserver/)
- Used Eureka for a naming server

### [What is Rabbit MQ? ](https://www.rabbitmq.com/)

### [What is distributed tracing? ](https://www.datadoghq.com/knowledge-center/distributed-tracing/#:~:text=Distributed%20tracing%20is%20a%20method,exhibit%20high%20latency%20or%20errors.)
- Used OpenZipkin for distributed tracing for this project.

### [What is a load balancer? ](https://www.nginx.com/resources/glossary/load-balancing/)

- Used Feign as a load balancer.

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



Using a framework in springboot called sleuth, we are able to put a unique id on the request that could go across multiple microservices so we are able to track the response that gets sent back. 

Circuit breaker basically allows a microservice to return a fallback response if the microservice that this current microservice is dependent on is slow or down. It helps reduce load.
