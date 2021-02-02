#Customize Ansible AWX

## Add a custom python import in AWK container

docker exec -it awx_task /bin/bash
bash-4.4# source /var/lib/awx/venv/ansible/bin/activate
(ansible) bash-4.4# pip install natsort

