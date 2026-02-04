#install ubuntu server in EC2
#Creating a new user called devops then give it sudo access 
#Create the below tree in devops library
/opt/devops
├── scripts
├── apps
└── logs
#Checking storage,process,listening ports 
#Used Commands 
adduser devops 
sudo chmod -aG sudo devops 
su - devops 
mkdir 
touch 
#Create a Dockerfile 
#Build Docker imange 
#Run HTML container in port 8080:80 using Nginx 

