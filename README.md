# ApacheWebServer

For this tech test, I have created an AWS EC2 with an Ubuntu 16.04 VM. After SSH'ing in to the VM, I installed Docker and Docker Compose that uses the Bitnami/Apache image to launch an Apache Web Server.

This Web Server can be found at http://54.246.222.13/


Due to not having prior experience of Puppet, Ansible or Terraform, I read through the documentation to try and plan what I would do with them in order to automate this process.

From what I can see, Terraform has can provide an AWS EC2 resource that allows instances to be created and deleted. I assume a Terraform script along these lines would provide a base for automating the creation of the EC2 instances. 
