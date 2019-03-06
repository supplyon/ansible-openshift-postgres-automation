# Hacky DB creation inside an OpenShift PostgreSQL Cluster instance

[PostgreSQL DB Module](https://docs.ansible.com/ansible/latest/modules/postgresql_db_module.html)
[PostgreSQL User Module](https://docs.ansible.com/ansible/latest/modules/postgresql_user_module.html)
[PostgreSQL Privs Module](https://docs.ansible.com/ansible/latest/modules/postgresql_privs_module.html)

* Requires running postgresql instance inside an OpenShift Cluster

* `pip install psycopg2`
* `ansible-playbook create-cluster-database.yaml`
* Pass required params to the playbook 
