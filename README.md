# Moving-Database-from-monolith
I will move database from monolith server to a separate EC2 instance as a first step towards elastic architecture.  

![image](https://github.com/dhruv14385/Moving-Database-from-monolith/assets/83332524/52e44b08-fb27-445a-b054-2f1c3502be4f)  

o	Initially, we have an EC2 instance containing apache webserver, MySQL database and wordpress application. We will move MySQL database to a new EC2 instance for high availability.
o	One click deployment link creates 2 numbers of EC2 instances.
o	Open monolith EC2 instance by using public IPv4. Create blog so that some data can be generated and saved in the database. 
o	Open instance connect, and using mysqldump command, take backup of existing data into .sql file. Refer to commands file in the repository.
o	Inject this .sql data into another EC2 instance which has only database. Do this by using private IPv4 of another EC2. Refer to video below for full demo from scratch.




