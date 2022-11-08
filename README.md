# AWS-Hive-implementation  
Hive is built on top of Apache Hadoop, which is an open-source framework used to efficiently store and process large datasets. As a result, Hive is closely integrated with Hadoop, and is designed to work quickly on petabytes of data
## Services  
### (1) AWS EC2  
Amazon EC2 instance is a virtual server on Amazon's Elastic Compute Cloud (EC2) for executing applications on the Amazon Web Services (AWS) architecture. Corporate customers can use the Amazon Elastic Compute Cloud (EC2) service to run applications in a computer environment. Amazon EC2 eliminates the requirement for upfront hardware investment, allowing customers to design and deploy projects quickly. Users can launch as many or as few virtual servers as they like, configure security and networking, and manage storage on Amazon EC2
### (2) Docker
Docker is a free and open-source containerization platform, and it enables programmers to package programs into containers. These standardized executable components combine application source code with the libraries and dependencies required to run that code in any environment
### (3) Hive
Apache Hive is a fault-tolerant distributed data warehouse that allows for massive-scale analytics. Using SQL, Hive will enable users to read, write, and manage petabytes of data. Hive is built on top of Apache Hadoop, an open-source platform for storing and processing large amounts of data. As a result, Hive is inextricably linked to Hadoop and is designed to process petabytes of data quickly. Hive is distinguished by its ability to query large datasets with a SQL-like interface utilizing Apache Tez or MapReduce.  

## Approach
### (1) Create a EC2 instance (t2.xlarge,additional rule: custom tcp, port range 0-10000)
### (2) Open terminal and connect to EC2 via pem file
### (3) Download Docker 
### (4) Copy file from local to ec2 & give permission
### (5) Start docker, access into docker_exp and run container
### (6) Port Forwarding to access various services
### (7) Run docker services (docker-compose up)
### (8) Run Hive
### (9) Interact hive wih spark (Run commands in Tensorflow or Jupytor)
