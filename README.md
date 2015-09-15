# capital-one-tech-talk

**_Containers are an approach to deployment that is changing how we build and deploy applications more consistently. Docker has created an easy to use CLI and standard for using containers that has quickly taken off among developers and then the world. Come and learn what Docker is all about and the fundamentals of getting started so you can use containerized applications and create your own. We will then look at designing and managing applications using Docker and what your application architecture will look like._** 

**_Mitch Ruebush is an Enterprise Architect at Capital One specializing in new software architectures like data streaming and microservices and changing the world._**

# Capital One

Capital One does:

+ Credit cards
+ Banking (actually a top 10 bank in the U.S.)

During its founding, Capital One diversified the types of credit cards that could be offered to consumers. 

# Containers

What is a container?

_A container runs on top of an OS using the underlying OS services, but isolating its process through namespace (mnt, pid, net, ipc, etc) and resources (cpu, memory, Block I/O, and network) through cgroups. It does not try to mimick the underlying hardware like a hypervisor for a VM and therefore cannot run different OSes. They all have to be the same. It allows for isolation of runtime environments to eliminate conflicts, very quick startup of applications on the same server, portability, and **predictable deploys**._

As one might think, the ability to share memory poses a security threat (like the fact that Docker runs root and can access whatever it wants). Even so, there are ways to get around security fears.

# Docker

Docker came around and made a nice, easy interface to use container technology. In essence, it's an ecosystem of tools for working with containers:

+ Docker Engine (Docker Daemon)
+ Docker Hub
+ Docker Machine
+ Docker Swarm (allows you to choose where you want to run, and how many)
+ Docker Compose (solves orchestration problems: how everything runs)
+ Kitematic (GUI for controlling all of the above)

# Installing Docker

See the [installation doc](https://docs.docker.com/installation)s and click on your platform. Docker runs on Linux and Windows Server 2016 Preview. Currently to run it on Windows or Mac OSX you need to use boot2docker or docker-machine. This will install a lightweight Linux instance running in a virtual machine. You can use boot2docker or docker-machine to manage this instance.



