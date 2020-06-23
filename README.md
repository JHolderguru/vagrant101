#Development Env and Vagrant 101

#### What is a environment
There are different types of environments.Development Testing and Production.This is the location where code runs and and data lives.Your machine is an environment because code runs and you develop software and web apps and other apps.
An environment aims to address these challenges by increasing how well IT operations and development teams collaborate in order to create an environment characterized by a unified team with a multidisciplinary skillset.

 This structure transforms the way that teams work together and the way that software is built by bridging the gap between “dev” and “ops” and applying effective DevOps tools to mitigate data silos. Overall, a DevOps environment increases visibility to reduce the risk of uncertainty, improves error and bug detection and mitigates bottlenecks and waste in the development process.




#### Advantages of Cloud
Where in the past, people would run applications or programs from software downloaded on a physical computer or server in their building,which would also require high maintainance like cleaning security and if it went down business would stop. However cloud computing allows people access to the same kinds of applications through the internet without the hustle of cleaning or security or worrying about it breaking.Cloud providers have come a long way to provide, Flexibility, Disaster Recovery, Automatic software updates, Capital-expenditure Free, Increased collaboration, Work from anywhere, Security, Competitiveness, Environmentally friendly


#### Dev Environment
A development environment is a collection of procedures and tools for developing, testing and debugging an application or program.

The development environment normally has three server tiers, called development, staging and production. All three tiers together are usually referred to as the DSP.

Development Server: Here is where the developer tests code and checks whether the application runs successfully with that code. Once the application has been tested and the developer feels that the code is working fine, the application then moves to the staging server.
Staging Server:This environment is made to look exactly like the production server environment. The application is tested on the staging server to check for reliability and to make sure it does not fail on the actual production server. This type of testing on the staging server is the final step before the application could be deployed on a production server. The application needs to be approved in order to deploy it on the production server.
Production Server: Once the approval is done, the application then becomes a part of this server.

#### 4 Pillars of DevOps
- Ease of use
- Flexibility
- Robustness
- Cost



#### DevOps Solutions
Development – writing code ,Py,SQL,HTML
Testing – strong automated testing then you can move faster (increase speed of learning and Developing) -- increase feedback loops increase innovation reduce bugs and all the 4 pillars.quicker build, testig and more deployments.
DevOps problems being that It may work on environment and not in another.





#### Virtual Box
VirtualBox is a powerful x86 and AMD64/Intel64 virtualization product for enterprise as well as home use. Not only is VirtualBox an extremely feature rich, high performance product for enterprise customers, it is also the only professional solution that is freely available as Open Source Software under the terms of the GNU General Public License

#### Vagrant
Vagrant is an open-source software product for building and maintaining portable virtual software development environments;[5] e.g., for VirtualBox, KVM, Hyper-V, Docker containers, VMware, and AWS. It tries to simplify the software configuration management of virtualizations in order to increase development productivity. Vagrant is written in the Ruby language, but its ecosystem supports development in a few languages.


#### Package manager

#### What is a package manager
A package manager or package-management system is a collection of software tools that automates the process of installing, upgrading, configuring, and removing computer programs for a computer's operating system in a consistent manner.. A package manager deals with packages, distributions of software and data in archive files.

#### wha is python's package manager? what about other languages?
pip

#### what are package managers for windows and mac?
chocolatey is a package manager for windows

#### what is the package manager for Ubuntu?
apt-get

to install- 

sudo apt-get update -y 

(-y is yes)

it will go off and update the packages , all the different ones that you can use.
then -

sudo apt-get install nginx -y

(looks like pp install, all code have different levels of package managers)

nginx (reverse proxy)has security features
Nginx, pronounced like “engine-ex”, is an open-source web server that, since its initial success as a web server, is now also used as a reverse proxy, HTTP cache, and load balancer.

Load balancing refers to efficiently distributing incoming network traffic across a group of backend servers, also known as a server farm or server pool.

Modern high‑traffic websites must serve hundreds of thousands, if not millions, of concurrent requests from users or clients and return the correct text, images, video, or application data, all in a fast and reliable manner. To cost‑effectively scale to meet these high volumes, modern computing best practice generally requires adding more servers.

A load balancer acts as the “traffic cop” sitting in front of your servers and routing client requests across all servers capable of fulfilling those requests in a manner that maximizes speed and capacity utilization and ensures that no one server is overworked, which could degrade performance. If a single server goes down, the load balancer redirects traffic to the remaining online servers. When a new server is added to the server group, the load balancer automatically starts to send requests to it.

Some high-profile companies using Nginx include Autodesk, Atlassian, Intuit, T-Mobile, GitLab, DuckDuckGo, Microsoft, IBM, Google, Adobe, Salesforce, VMWare, Xerox, LinkedIn, Cisco, Facebook, Target, Citrix Systems, Twitter, Apple, Intel, and many more.
While Apache is the most popular overall option, Nginx is actually the most popular web server among high-traffic websites.




