#Python for Beginners Project
In this project I went through the basics/foundations blocks of python. 
An assignment brief was used to to navigate through subject matter (basics/foundation blocks of python).
The assignment brief mainly takes effect in the variables.py
The topics in foundation blocks was : list, loop,turple
The project also looks at Python on Aws. ie how to import libray, specify regions and get ist of availble resource on AWS console


#Assignment brief
Provision these AMI using 
eu-west-2  - ami- 0d729d2846a86a9e7, 
eu-west-1 this ami-  ami-0c1bc246476a5572b
us-east-1 this ami ami-0022f774911c1d690
Tasks:
Create a 
1. list of all the 3 amis and assign it to a variable called ami_list
2. a for loop and loop through the ami_list variable and print each ami out
3. atuple of all the 3 amis and assign it to a variable called regions_tuple
4. a for loop and loop through the regions_tuple variable and print out the ami name if the region is equal to us-east-1 
5. a dictionary which is a key-value pair of region to ami and assign it to a variable called region_ami_dict
6. a for loop and loop through the regions_tuple variable and print each region
Import the
 boto3 library and get a list of available resources from your aws account using the get_available_resources() function


#Prerequisite
The lastest version of python is installed (python3) with necessary plugins and Boto3 is intalled. 
Visit https://www.python.org/downloads/macos/ to install latest version of python
Also watch https://youtu.be/YYXdXT2l-Gg for step by step tutorial on how to install and understand python for beginners
AWS config had been configured on your terminal. 
This will allow you list availble resources. 