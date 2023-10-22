# SampleAWS01
Question1
1) A company runs a public-facing three-tier web application in a VPC across multiple Availability Zones.
Amazon EC2 instances for the application tier running in private subnets need to download software
patches from the internet. However, the EC2 instances cannot be directly accessible from the internet.
Which actions should be taken to allow the EC2 instances to download the needed patches? (Select
TWO.)
A) Configure a NAT gateway in a public subnet.
B) Define a custom route table with a route to the NAT gateway for internet traffic and associate it with the
private subnets for the application tier.
C) Assign Elastic IP addresses to the EC2 instances.
D) Define a custom route table with a route to the internet gateway for internet traffic and associate it with
the private subnets for the application tier.
E) Configure a NAT instance in a private subnet.
