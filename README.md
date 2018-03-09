# Ansible-openshiftNodeConfig
Simple ansible playbook preparing new OpenShift node server

Before running this playbook, please ensure that you change the following:
* Put your SSH public key (from master node) in 'root_deploy_authorized_keys' variable,
* Put your block device to be used by docker in 'disk_dev' variable.
* Customize your ansible host file.
