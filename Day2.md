# S3
- S3 is basically a storage engine.
- Cost of s3 is very cheap.
- You can store any type of files inside it.(like a google drive).
- The total volume of data and number of objects you can store are unlimited.
- To store all type of files and folders , first we have to create one bucket.
- While creating bucket, bucket name must be unique accross the aws.(means top parent(folder) name should be unique)
- Inside bucket you can create multiple folders and you can upload and download files.
- S3 supports webhosting.Generally you can host or configure static web pages inside it.Once configured you can make basic HTML pages
 using the static URL.


# Security Groups
- Security group is same as firewall which controls the network traffic and provides security for instance.
- For any instance we can specify one or more security groups as per our requirements.
- We can also use default security groups.
- Using security groups we can choose or change ports and set protocols as per our requirement.
- There are two rules inside security groups, Inbound and outbound rule.


**Inbound rule**
- Basically inbound rule handles the incomming traffic coming to your instances.For this you have to add inbound rule.

**Outbound rule**
- Outbound rule handles outgoing traffic from your instances.To connect internet or any browser you have to add outbound rule.
