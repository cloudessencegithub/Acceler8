# AWS CloudFront

## Learning Objectives
By the end of this lesson, students will be able to:
- Understand the concepts and principles of CloudFront
- Create a CloudFront distribution

### Estimated Time: 3 weeks

## Introduction
Amazon CloudFront is a web service that speeds up distribution of your static and dynamic web content, such as .html, .css, .js, and image files, to your users. CloudFront delivers your content through a worldwide network of data centers called edge locations. When a user requests content that you're serving with CloudFront, the user is routed to the edge location that provides the lowest latency (time delay), so that content is delivered with the best possible performance.

## Why is it important to know?
- Global Content Delivery: CloudFront is a content delivery network (CDN) service that securely delivers data, videos, applications, and APIs to users globally with low latency and high transfer speeds. If you are working on applications that have users around the world, knowing how to set up and use CloudFront can significantly improve user experience
- Performance Optimization: CloudFront is designed to work seamlessly with services like Amazon S3, EC2, and Elastic Load Balancing. By placing CloudFront in front of these services, you can cache content closer to your users, thereby reducing the load on your backend systems and improving overall application performance.
- Security: CloudFront provides several features to secure your applications, including HTTPS for all communication, AWS Shield for DDoS mitigation, AWS WAF (Web Application Firewall) integration to protect against common web exploits, and field-level encryption for sensitive data. Understanding how to configure and use these features can enhance the security of your applications.
- Cost Efficiency: By caching content at edge locations, CloudFront reduces the amount of data that needs to be transferred from your origin servers, which can help reduce your data transfer costs. Moreover, AWS offers a pay-as-you-go model for CloudFront, which means you only pay for the data you actually deliver through the network.
- Dynamic and Static Content: CloudFront isn't only for static content; it can also speed up the delivery of dynamic content (like HTML, CSS, or JavaScript files that are tailored for individual users), which can be a huge advantage for personalized, real-time, or data-intensive applications.
- Integration with AWS Ecosystem: CloudFront integrates well with other AWS services such as S3, EC2, Elastic Load Balancing, Route 53, and AWS Lambda@Edge, which allows you to run Lambda functions closer to the user to customize content.
- Data Analytics: CloudFront provides multiple ways to analyze your content delivery, including raw logs, AWS CloudTrail integration for API logging, and real-time metrics in Amazon CloudWatch. This can help you understand the usage patterns of your users and make informed decisions about your application.

## Resources
- [AWS CloudFront](https://www.simplilearn.com/tutorials/aws-tutorial/aws-cloudfront)
- [AWS CloudFront Tutorial](https://www.sitepoint.com/aws-cloudfront-tutorial-setup-and-configuration/)

------

_If you spot any bugs or issues in this activity, you can [open an issue with your proposed change.](https://github.com/cloudessencegithub/Acceler8/issues/new)_
