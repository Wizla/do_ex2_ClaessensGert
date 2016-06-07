#Lamp-Stack with Ansible

##Commands to run
ssh-keygen -t rsa -b 2048 
ssh-keyscan lb web1 web2 >> .ssh/known_hosts
cat .ssh/known_hosts