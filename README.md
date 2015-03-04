**Amazon-AMI**


HDP 2.1 with Spark 1.1

Created an Hortonworks AMI with Spark 1.1

**Login** 


Login with ec2-user

* Check if ambari sever is running

`sudo ambari-server status`

* Start Ambari Server

`sudo ambari-server start`

**Ambari UI**


http://{ec2-host}:8080/

u/p - admin/admin

Check and start your HDP services

**Spark** 


Spark 1.1 is installed under ec2-user

you should be able to invoke spark-shell from command line

Enjoy

Questions

Magic Coder - webmonkeydude@gmail.com


