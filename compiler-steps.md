# How to run c++ code stepwise
1. Login to AWS console and Start your EC2.
2. In Mobaxterm app insert all details such as ip address, password file, username.
3. Next command- sudo yum -y install gcc-c++
	This command will install gcc compiler.
4. create one directory- mkdir <name_of_directory>
5. Inside that directory create one file 
	vi first.cpp
6. Now you will see text editor to edit press "i" and start writing your code.
7. Once you finish writing press "esc" and to write the code on file ":w".
   Exit the editor by typing ":q".
8. You will see command line window after exiting the editor now u have to compile and run 
   the code you have written in file.
9. To compile the code -> g++ first.cpp -o first
   To run -> ./first
10. This way you can create and run the programs of c++.
