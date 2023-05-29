# AWS EC2 Exercise

## Learning Objectives
- Understand the concepts and principles of EC2

### Estimated Time: 1 hour

## Exercise
These exercises should help you practice your knowledge of AWS EC2. Good luck!

### Instructions
IMPORTANT NOTE: Read all instructions carefully before starting the exercise.

- Launch an EC2 instance using the AWS Management Console. Set up SSH key pairs, select an appropriate AMI (Amazon Machine Image), choose an instance type, and configure security groups.
- Once your instance is launched, SSH into it from your local machine using the key pair you created during the setup. For Windows instances, you can use RDP (Remote Desktop Protocol) to connect to your instance.
- Attach an additional EBS (Elastic Block Store) volume to the instance you launched, format it, and mount it in the operating system. Try creating an AMI from this instance, launch a new instance from this AMI, and verify if the data in the attached volume is preserved.
- Write a user data script that installs a web server (like Apache or Nginx) and a sample web page while launching an instance. Once the instance is launched, browse to the public IP/DNS of your instance to view the page.
- Create a security group that only allows access to your IP address. Apply this security group to an EC2 instance and verify the access.
- Create an AMI of your EC2 instance and use that AMI to launch another instance. Check if all the configurations and data have been copied to the new instance.
- Launch two instances that serve a simple web page. Place them behind an Application Load Balancer. Test the load balancer's functionality by accessing its DNS name.
- Configure an Auto Scaling group that uses the load balancer you created. Test whether new instances are created when CPU utilization is high and terminated when CPU utilization is low.
- Request a Spot Instance and understand the cost difference compared to On-Demand instances. Monitor the Spot Instance request and understand the states.
- From within an EC2 instance, access the instance metadata to retrieve information about the instance such as public IP, region, and more.

### Submit your work
- Create a document with the answers/commands you used to complete the exercise.
- Add screenshots of the output of the commands you used to complete the exercise.
- Submit your work on the slack channel for this activity.

------

_If you spot any bugs or issues in this activity, you can [open an issue with your proposed change.](https://github.com/cloudessencegithub/Acceler8/issues/new)_
