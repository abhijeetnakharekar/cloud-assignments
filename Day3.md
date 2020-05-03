# SSH(Secure Shell)
- We use ssh for remote login.
- ssh command [ssh -i (.private file path) username@ip] 
- When we create any instance or ec2 on clound, after creating it we need to login or access that instance. So for that remote login
  we use ssh.
- There are two keys keys, private key and public key. We use these keys for remote login.
- Private key contains (.pem) private file and public key is stored by aws in ec-2(instance).Private key is read only file.
- Private file is more secure than password. So they give us .pem file which is encrypted.
- When you pass .pem file at that time contents of .pem file must be match with public key which is inside ec-2(instance). If it is 
  matched then u will get login. Othewise you cannot login.



# commands
1. $		      means you are not root(admin) user.
2. sudo su	  use to change user(switch to root user).
3. ls		      list dir/file.
4. pwd		    print working dir.
5. cd		      change dir.
6. ~		      home dir of current user.
7. mkdir		  make dir.
8. vi 		    creates text file.
9. i		      insert mode.
10. w		      write in the file.
11. q		      quit exit from current file.




# Path
-	absolute pathnames			                      

an absolute pathname begins with  			        
the root dir and follow the tree branch			    
until the path to the desired dir/file		    	
is completed.

/user/bin/home/ec-2 user/test

- Relative pathnames

. means working dir
.. working dir,parent dir
start from working dir




# RDS(Relational Database Service)
- RDS service provides database connectivity through the Internet.
- RDS is used to set up, manage and scale a relational database instance in the cloud.
- You can create, configure, manage and delete an RDS instance, which is a cloud database environment, along with
  the compute and storage resources it uses.
- RDS support different versions of database engines.
- when you creates a database instance you can specify an engine version.


















