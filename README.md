# Developer Operations (DevOps/Infrastructure) Recruitment Test

## Please before you take this test, Ensure you posses the following skills
1.	Strong linux administration skills
2.	Familiarity with containerization specifically Docker and its echo system (docker-compose, docker-machine and docker-swarm). Some of the things you need to know are
a.	Can create a Dockerfile and build an image from it
b.	Linking multiple containers manually and with the use of docker-compose
c.	Can use docker-machine to spin up remote servers from different cloud providers as well as regular VPS servers
d.	Have played with docker-swarm
e.	Can push an image to both dockerhub and a private registry like gitlab
3.	You know what Continuous Integration and Continuous Delivery means and can set up one with Gitlab
4.	Understands both pre and post git hooks and is comfortable writing shell scripts
5.	Can set up automated Testing on both Bitbucket and Gitlab using their pipelines
6.	Basic linux security practices like avoiding root account in ssh, setting up firewall in a vps
7.	Experience with the python programming language and familiarity with deployment tools such as ansible, fabric, saltstack, chef, puppet etc.

The test is to create either a bitbucket or a gitlab pipeline that can automatically run the tests on <Developer Repository>. 

The repository(ies) should be publicly accessible and the links should be sent as an issue to this repository on github.

And finally, the containers should be saved on gitlabs private registry for whatever repository you use. 

#### NB: For the private registry, this can only be done on gitlab. 

For any question or more explanation, please place an issue on this repository
