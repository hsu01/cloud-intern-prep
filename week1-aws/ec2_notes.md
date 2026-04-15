## EC2 Key Takeaways

- EC2 is a virtual server in AWS
- AMI is a template for launching instances
- Instance type determines CPU and memory
- Security groups act as firewalls

## Important Learning

- My web server did not work initially
- Reason: port 80 was blocked in security group
- Fix: allowed HTTP inbound traffic
- Lesson: networking rules directly affect accessibility

## New Concepts

- User data can automate setup (install web server)
- EBS is storage attached to EC2
- Instances can be resized based on needs
- Termination protection prevents accidental deletion
