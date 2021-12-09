AWS-BOTO-Playbook-example  
====================  

This is an example of using the AWS BOTO3 python Library in Ansible to  
provision EC2 instances/VMs using an Ansible playbook.  
I wrote this a while back.  

Personally, I would use Terraform https://www.terraform.io/ as it  
will work with a wide variety of hosting/cloud providers as well as support  
hypervisors such as KVM/LibVirt, VMWare, Xen and even kubernetes containers. 
https://registry.terraform.io/browse/providers   
"Vendor Lock" from a service provider is a form of technical debt we should all avoid  
as much as possible.  

Requirements
============
I will not go into too much detail for using this as my preference is stated above.  
An AWS account would be needed.  
A free tier account will work fine.  
You will need to install Boto on the machine you run your Ansible playbooks on.

<pre>  
$ pip install boto3    
</pre>  

License
=======

MIT  


Author Information
================
Roy Kim  
https://github.com/customizedcode  
customizedcode.us  
