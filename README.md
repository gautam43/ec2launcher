ec2_launcher
=========

Launch the EC2 Instances for the configuration of Kubernetes cluster over AWS.
It launches One Master node and Two Worker nodes.
Master node is named as "master" and Worker node as worker node 1 and 2.

Requirements
------------

For connecting and Using the Resources of AWS Cloud, boto3 library is required as the SDK.
Role Variables
--------------

1.imageId - This variable should be used to pass the id of the image used to launch the instances.
2.instType - This variable is used to specify the type of ec2 instance like t2.micro is one of the example.
3.region - Used to specify the region in which you want to launch the instance
4.sg - specify the security group name
5.key - Used to specify the key with its proper path  

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: localhost
      roles:
         - role: username.ec2_launcher

License
-------

BSD

Author Information
------------------

Any Query Feel Free to contact me:
https://www.linkedin.com/in/gautam-khatri-8891b3127/
