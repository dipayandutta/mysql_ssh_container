# A Mysql Container sevice , with ssh connection to the container 

# To run the container use the following command 
docker run --name mysql_ssh -d -i -t -p 2222:22 dipayandutta/mysql_ssh bash

# Then ssh on the container using the following command
ssh dipayan@localhost -p 2222
# password -> node 

