This project contains scripts to let you create and delete nodes from Rundeck, without using third-party node providers. 

It takes advantage of Rundeck jobs power to modify resources files using provided parameters: Project name, Node name, hostame, etc.

Install:

- Copy rundeckNodeCtl python script into /usr/local/bin
- Create a project for node administration, for Example *Nodes_Admin*
- Create a job for adding Linux nodes by uploading the job defininion named *Add_Linux_node.xml*
- Create a job for removing nodes by uploading the job defininion named *Remove_node.xml*
- Then from *Node_Admin > Jobs* run the corresponding job to add or remove nodes.



 
