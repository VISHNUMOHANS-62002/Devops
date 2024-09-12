# Devops
Dev-->Development team
Ops-->Operation team
DevOp and CICD (Docker&Kubernetes)
Development team usually deals with building codes and sharing ,the operation team just goes throug the testing,bug fixing,etc....Operation team are usually responsibile for ensuring and implementing projects in the client field.

Scenario1:
Person1     Person2     Person3
(windows)    (Mac)       (Linux)

Virtualisation
I could be able to run virtual OS on my local OS.

Basic Arch:

Virtual OS
---------->
Basic OS

Adv Arch:(Multiple Virtual Os)(Sol:series execution ,borrowing)

Virtual Os      Virtual Os


Basic OS

Container(Docker)
Virtual Os      Virtual Os
      
       Docker Engine:It just make sure the inernal resource sharing takes place correctly


Basic OS

Docker we will be dealing with EC2  Instance>>Images&Container
Kubernates(Orchestra)
Node>>MasterNode>>ChildNode

Docker 
>>Image(Parent)
>>Containers(Servers)
Client Server Architecture

Kubernetes
>>Docker Demon(Intialization)
>>Docker Client(Client)
>>Docker Swarm(Orchestra||Master)


>>Master Node
>>Child Node
   >>POD(Container)
   >>Development(It will keep a close eye on POD)

 Archiecture of Docker
 >>Image
   >>Container1  
   >>Container2 
   >>Container3  
 Archiecture of Kubernetes
 >>Master Node 
 Child node-1        Child node-2       Child node-3       Development 

 Docker>>Kubernetes

 Aws=>Ec2
 Client
               Kubernetes
 Server
 NGINX(Light weight Server)              