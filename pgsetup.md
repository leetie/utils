set up info for postgresql for Rails development environment on my machine. 

* Make postgres DB
	naming convention in rails is to look for the DB with the default user being the current system user, with the DB name of "projectname_development"

```bash
sudo -u postgres postgresql
```
\l to show DBs, \du to show Roles

* Make DB for development environment
```bash
CREATE DATABASE myproject_development
OWNER = whateveruser;
```

