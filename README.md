# aws-rds-db
Ansible play to create DB in AWS RDS

Task will create Postgresql database 
add 2x users, admin and read-only user 
will create passwords and store them in Hashi Vault 
Read password from Vault and in case Env is Dev, will send passwords to user in email else email doesnt contain password




