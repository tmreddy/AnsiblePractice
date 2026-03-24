add user user 
create files copy
install packages state present 
uninstall packages state absent
localhost ansible_connection=local
-m for module 
-i from inventorty 
all for all hosts
local for localhost
web for web servers
modules
ping for pinning 
user for adding user
copy for creating a file 
apt for installing 
service for starting or stopping a service 

ansible -i inventory.ini local -m command -a "sudo apt remove tree -y"


