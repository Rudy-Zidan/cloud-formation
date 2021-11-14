## Cloud Formation template for web applications infrastructure

### Files
 - network.yml: will prepare your network resources needed
   - vpc
   - internet gateway
   - nat gateways
   - elastic ips
   - public subnets
   - private subnets
   - routing rules
   - routing tabless
 - servers.yml: will prepare your computation resources needed
   - security groups
   - autoscaling group
   - load balancer
   - launch group (ec2 image, count, userData(optional, you can use ansible for application setup))

### Cloud Diagram
![Alt text](cloud_architecture.jpeg?raw=true "Cloud Architecture")