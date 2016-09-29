# nclouds-test
Ansible playbook for creating RDS MySQL DB instance and a Read-Replica

Current playbook consists of two roles: one for creating a RDS MYSQL DB instance and another is for creating a read replica of DB Instance. 

In order to run this playbook, aws cli configuration must be done on the host machine with aws secure credentials. We can do that using the following command.

``` bash
aws configure
```
