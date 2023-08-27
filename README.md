# Project--Docker-4-Muiti-Build-Task

<table>
REACT---NODE---MongoDB  
  
</table>

**Here I have used Amazon AWS as the cloud hosting provider to deploy the multiple containers on the AWS EC2 first where we manually installed the image on our local machine
pushed it into the docker hub, pulled it from there to AWS then installed docker there and made our application on the remote machine manually.**

**After this we shifted to AWS ECS for managing our containers automatically. This saves a lot of time and we don't need them to keep a check and update our code there.**

**Also we removed our Mongodb container which we are creating there in our remote machine using (EC2) and (ECS) and instead shifted to Mongo Atlas which under the roof 
uses the specified cloud providers like AWS, Azure, and Google Cloud. By this we again remove the disadvantage of using the database container which is scaling and managing is
very difficult. Backup is difficult and security is also a major concern there. But we have removed that problem by connecting to the Mongodb atlas.Here we are using two different 
tasks for frontend and backend as react and node both are exposed to the same port so we shifted from one ecs task to multi ecs task for creating creating two servers on differnt
host for two different containers.**

Layout Config is 
REACT  ->   NODE JS -> MongoDB Atlas
