# aws-nti
our task is to create VPC with 2 different zones each zone contain 2 subnets one public and the other one is private 
after creating this environment we have to run apache server on the private subnets in each zone after creating ec2 for each subnet 
after that we should run Nginx server on the public subnets in each zone 
then we should create 2 targets group 1 for each public subnets and the other for the private subnets 
then we create 2 load balancers one for each target to handle the internet traffic 
