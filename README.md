# DB creation inside an OpenShift PostgreSQL Cluster instance

## Requirements

* Requires running postgresql instance inside an OpenShift Cluster

* `pip install psycopg2`
* `ansible-playbook create-cluster-database.yaml`
* Pass required parameters to the playbook, e.g.

```sh
ansible-playbook create-azure-database.yaml -e POSTGRESQL_LOGIN_HOST=$DATABASE_URL -e POSTGRESQL_ADMIN_USER=$DATABASE_ADMIN_USER -e POSTGRESQL_ADMIN_PW=$DATABASE_ADMIN_USER -e DATABASE_NAME=$DATABASE_NAME -e ROLE_PASSWORD=$ROLE_PASSWORD
```
