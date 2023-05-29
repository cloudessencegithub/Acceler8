# AWS VPC Networking Exercise

## Learning Objectives
- Understand the concepts and principles of VPC networking

### Estimated Time: 3 weeks

## Exercise
These exercises should help you practice your knowledge of AWS VPC networking. Good luck!

### Instructions
IMPORTANT NOTE: Read all instructions carefully before starting the exercise.

- Set up a VPC with a single public subnet. Then, create an EC2 instance within that subnet. Verify that the instance has Internet access.
- Create a VPC with both public and private subnets. Set up proper route tables for each. Deploy an EC2 instance in each subnet, and test internet connectivity.
- Create a few security groups and network ACLs with different rules. Assign them to different instances and test their effectiveness.
- Add a NAT instance or a NAT Gateway to a VPC with a private subnet. Ensure instances in the private subnet can access the internet.
- Create two VPCs in the same region but with different CIDR blocks. Set up VPC peering between them and ensure instances in each VPC can communicate with each other.
- Set up a VPC endpoint for an AWS service like S3 or DynamoDB, and verify that instances in the private subnet can access those services without traversing the public internet.

### Submit your work
- Create a document with the answers/commands you used to complete the exercise.
- Add screenshots of the output of the commands you used to complete the exercise.
- Submit your work on the slack channel for this activity.

------

_If you spot any bugs or issues in this activity, you can [open an issue with your proposed change.](https://github.com/cloudessencegithub/Acceler8/issues/new)_