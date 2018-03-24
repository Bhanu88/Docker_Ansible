# Docker_Ansible
for useing this code you need to perform following steps

1.Edt Hosts file - In host file please provide the ip address and user name of the host where docker is installed

when you are done with editig please check if the docker host is reachable by ansible by running following command 

ansible dock -m ping

then if the test is successful 

please run following command for the building a apache2 docker 
image then pushing it in the repo and then creating a docker container with builded apache Docker image

ansible-playbook docker_build.yml
