# Implementation of GLPI Project
## Context
We will implement a "GLPI Project" container by way of "docker-compose".

### Procedure
1. Implementation of ocs_inventory

   *this software are very important for the "glpi project" because it makes it possible to carry out inventory on the hardware configuration, software. We can be to visualize on web interface* 
   
3. Implementation of mysql_server
  
    *This database management system can be to store informations about the hardware configuration and software inventory*
    
5. Implementation of GLPI_Project

  *The most important software. He can be to realize inventory*
  
  #### Test
  - Using the plateform of Docker : https://labs.play-with-docker.com/
  - realize a git clone to receipt dockerfile : https://github.com/cbourgeois1/EPSI-docker.git
  - Installation in first, mysql-server [mysql.png] (command : **docker-compose up**)
  - Installation of glpi ![glpi_install]
  - Print of the container's listing [docker_list.png] (command : **docker ps**)
  - Testing to the GLPI interface (success) [interface.png]
  - Testing to the MYSQL interface (fail)
