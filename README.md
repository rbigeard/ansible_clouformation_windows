# Ansible Cloudformation Windows Provisioning Example

This is a simple example of Ansible creating a cloudformation stack comprising of one Windows Server 2012 VM in AWS.

Once the stack is created, Ansible performs some configuration on the newly created Windows server.

It leverages the ec2_win_password module which retrieves Windows passwords based on your Windows key file.

The windows_aws_key_file  variable in group_vars/all.yml must point to your AWS Windows key file.
