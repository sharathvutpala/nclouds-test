# nclouds-test
Ansible playbook for creating RDS MySQL DB instance and a Read-Replica

Current playbook consists of two roles: one for creating a RDS MYSQL DB instance and another is for creating a read replica of DB Instance. 

In order to run this playbook, aws cli configuration must be done on the host machine with aws secure credentials. We can do that using the following command.

``` bash
aws configure
```

Once the aws cli is configured, we can run the playbook with the following command.

``` bash
ansible-playbook rds.yml -vvv
```
Here -vvv indicates verbosity level. 

Facts related to Read-replica of MySQL DB instance are gathered in ./facts/facts.
