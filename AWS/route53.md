# AWS Route53

## Learning Objectives
By the end of this lesson, students will be able to:
- Understand the concepts and principles of Route53
- Create a hosted zone
- Create a record set
- Use Route53 to route traffic to AWS resources

### Estimated Time: 3 weeks

## Introduction
Amazon Route 53 is a highly available and scalable cloud Domain Name System (DNS) web service. It is designed to give developers and businesses an extremely reliable and cost-effective way to route end users to Internet applications by translating names like www.example.com into the numeric IP addresses like

## Why is it important to know?
- Domain Registration: Route 53 allows you to register new domain names for your applications, making it the first point of contact for establishing your presence on the web.
- DNS Routing: Route 53 translates friendly domain names like www.example.com into numeric IP addresses like 192.0.2.1 that computers use to connect to each other. Understanding how this works is key to ensuring your applications are reachable.
- Traffic Flow: Route 53 offers sophisticated traffic flow policies. You can use it to route users to different endpoints based on a variety of conditions like geographic location, latency, health checks, and more. This allows you to increase your application's performance and availability.
- Integration with AWS Services: Route 53 is designed to work seamlessly with other AWS services like EC2, S3, CloudFront, ELB, and more. This allows you to easily route traffic to these services, creating a smooth experience for your users.
- Health Checks and Failover: Route 53 can perform health checks on your resources and implement DNS failover to reroute traffic to healthy resources. This is crucial for maintaining high availability and reliability for your applications.
- Scalability: Route 53 is built to scale automatically in response to DNS query volume, making it a key tool for maintaining the performance of your application as it grows.
- Security: Route 53 supports DNSSEC, which helps to protect your domain from DNS spoofing attacks.
- Private DNS for Amazon VPC: You can use Route 53 to manage DNS names and resolve them within your Virtual Private Clouds (VPCs). This can be useful for internal communication within your AWS environment.

## Resources
- [AWS Route53](https://www.tutorialspoint.com/amazon_web_services/amazon_web_services_route_53.htm)
- [AWS Route53 Tutorial](https://medium.com/tribalscale/how-to-configure-aws-route-53-c8fa99ce66fb)
- [Watch this video](https://www.youtube.com/watch?v=n7yTp5xg49w)

------

_If you spot any bugs or issues in this activity, you can [open an issue with your proposed change.](https://github.com/cloudessencegithub/Acceler8/issues/new)_
