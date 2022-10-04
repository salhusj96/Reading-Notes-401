# **Compute Abstractions on AWS**
## **Separation of Duties**
- AWS can be defined as a cloud computing solution
- There exists a 'perimeter' between what AWS does and what the user does within the cloud
  - These responsibilties vary based on the services being used
## **Different Abstraction Levels**
- Computing can take place at different layers of abstraction
- AWS provides a multitude of services that compute at different abstraction layers
- The layers can be defined like so:
  - **Virtual Machine/Instance Abstraction**
    - The very first abstraction on AWS, introduced in 2006 **(EC2)**
    - User retains responsibility of  guest OS, applicationsd, middleware, and their lifecycles
    - Exists at the edge between user and provider
  - **Container Abstraction**
    - Containers virtualize an OS to allow separated applications with different/incompatible software dependencies to run
    - Modern container-solutions typically implemented in two logical pieces:
      - *Control Plane*: exposes API and interfaces to define, deploy, and lifecycle containers, AKA container orchestration layer.
      - *Data Plane*: responsible for providing hardware capacity, connects to a network.
    - Amazon released **ECS** as a solution to free customers from having to manage control planes.
  - **Function Abstraction**
    - Allows a customer to run a single function, rather than an entire OS instance to run code **(AWS Lambda)**
  - **Bare Metal Abstraction**
    - Amazon EC2 bare metal, essentially gives users direct access to hardware
  - **Full Container Abstraction**
    - An option presented by **AWS Fargate** to turn the *Data Plane* into a managed service
### **Full Diagram**
![AWS Abstraction](https://d2908q01vomqb2.cloudfront.net/fc074d501302eb2b93e2554793fcaf50b3bf7291/2018/09/06/Abstraction8-1024x575.png)
---
Source: [Comput Abstractions on AWS](https://aws.amazon.com/blogs/architecture/compute-abstractions-on-aws-a-visual-story/)