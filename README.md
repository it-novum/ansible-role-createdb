# Ansible Role - Create a datebase

Creates a database (currently only mysql is supported)

## Variables

All variables are required.

* createdb_dbs: Database system (only mysql supported)
* createdb_config: path to an ini file where the password will be stored
* createdb_host: the host address of mysql (usually localhost)
* createdb_user: the user that should be created/updated
* createdb_password: the password for the user
* createdb_database: The database where the user get all privileges granted
