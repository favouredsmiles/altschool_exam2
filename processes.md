 1. provisioning of two Ubuntu-based servers, named “Master” and “Slave”, using Vagrant.
 ![alt text](<Images/Screenshot 2024-04-17 144838.png>)

 2. creating a bash script to automate the deployment of a LAMP (Linux, Apache, MySQL, PHP) stack on the master node
   ![alt text](Images/script.png)
 3. apache default page for the master node
   ![alt text](Images/master_apache.png)
 4.  laravel page after successful installation of LAMP and Laravel
![alt text](Images/laravel_master.png)
 5. screenshot of the inventory file which contains the ip address of the slave node
  ![alt text](Images/inventory.png)
 6. successfully ping to the slave node from the master
   ![alt text](Images/ping.png)
 7. successful ansible-playbook command
![alt text](Images/successful-playbook.png)
 8. successfully loading the slave ip address on a browser
   ![alt text](Images/laravel-slave.png)