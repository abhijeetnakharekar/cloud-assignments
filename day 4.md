How to communicate EC2 with s3?
different ways to communicate-
1. AWS cli
2. Sdk is available in java, python(boto3-package), nodejs

command for communicating with s3
aws<service_name> -[command option]
eg. aws s3 ls
it will list all the buckets in s3 but this command will not work because services cannot 
communicate directly.

IAM(Identity access management) ROLES
In simple words IAM ROLES is an identity you can attach with any services.
Rules are attached to IAM roles which contains authorization, rules are called as Policies.
You can create unlimited IAM roles.
Policies are created in JSON containing key value pair.
Policies are attached to IAM roles and these IAM roles are attached to ec2 so that you can 
communicate with s3.

How to create IAM roles?
1. sign in to AWS
2. click on roles in left hand side
3. create IAM role
4. select EC2 and next go to permission
5. type s3 in search box of created policies select amazons3fullaccess
6. click on next tags
7. review- add name of role description is already given u can edit it also
8. create

Now we have to attach created IAM role to EC2
1. Go to EC2
2. Click on action->instance setting->attach/replace/IAM role
3. now u will see list of roles click on ur created role 
4. apply then close

Now you can apply above command aws s3 ls and it will show you list of buckets in it.
aws s3 ls s3://<bucket name> will show what is inside ur bucket
	in output if PRE is written then that is ur folder and if time date is written it is your file
ls -r test/
	to show all things inside test
for aws cli->
aws s3 ls --recursive<bucket_name>

Amzon Machine Image
when u format pc u need os, ISO file is available for os which will u can store in CD or pendrive

usernames->
ubuntu->ubuntu
linux->ec2
windows->administrator

Availability Zone
In case of natural calamities the datacenter may get destroyed and this will cause all services to stop
at that center.
To avoid this amazon has created availability zones under one data center according to area.
There are different services on different data centers.
If all datacenters in one region are destroyed then we work on multi regions, the traffic is
diverted to another region.

cp-> copy
cp source                             dest
cp /home/ec2-user/test/dbda/dac2.txt /home/ec2-user/test/dac/

mv-> move
mv source      dest
mv dbda2.txt ../dbda/

rm->remove delete
rm<file path>
rm dac2.txt

ls -a
hidden files(.)

history
shows history of commands

ctrl+r
type command alphabet eg mkdir
it will show recent command of mkdir if u want to change the command press ctrl+r till u get
ur desired command.


 
	

