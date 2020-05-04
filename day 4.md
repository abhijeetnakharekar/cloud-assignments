# How to communicate EC2 with s3?
**different ways to communicate**
1. AWS cli
2. Sdk is available in java, python(boto3-package), nodejs

# command for communicating with s3
aws<service_name> -[command option]
eg. aws s3 ls
it will list all the buckets in s3 but this command will not work because services cannot 
communicate directly.

# IAM(Identity access management) ROLES
1. In simple words IAM ROLES is an identity you can attach with any services.
2. Rules are attached to IAM roles which contains authorization, rules are called as Policies.
3. You can create unlimited IAM roles.
4. Policies are created in JSON containing key value pair.
5. Policies are attached to IAM roles and these IAM roles are attached to ec2 so that you can 
   communicate with s3.
***

# Availability Zone
In case of natural calamities the datacenter may get destroyed and this will cause all services to stop
at that center.
To avoid this amazon has created availability zones under one data center according to area.
There are different services on different data centers.
If all datacenters in one region are destroyed then we work on multi regions, the traffic is
diverted to another region.
***
## Some important commands
**cp-  copy**
- cp source dest
- cp /home/ec2-user/test/dbda/dac2.txt /home/ec2-user/test/dac/

**mv-> move**
- mv source      dest
- mv dbda2.txt ../dbda/

**rm->remove delete**
- rm<file path>
- rm dac2.txt

**ls -a**
- hidden files(.)

**history**
- shows history of commands

**ctrl+r**
- type command alphabet eg mkdir
- it will show recent command of mkdir if u want to change the command press ctrl+r till u get
ur desired command.


 
	

