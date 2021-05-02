#  Start with Ansible configuration manager
# Description
In this project, we have 4 role which are responsible for configure our system madular.
role postgres : for installing and configuring postgres database server.
role nginx : for installing and configuring nginx webserver and deploying the code.
role common : for configuring common requirment of servers.
role learning : for learning purpose, I wanted to test variable priority and test loops in ansible.
during learning role I found that variable priority is like : 
1) group_vars 
2) 2) vars
3) 3) default 

**1.An ansible playbook for executing the configs**

#ansible-playbook site.yml -i inventory/sample/hosts.yml   
