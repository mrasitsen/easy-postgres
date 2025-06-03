# easy-postgres
easy postgres setup with docker-compose  <br> 

to run:  <br> 

docker-compose up -d  <br> 

It creates a container for postgress and pgadmin, and automaticaly connects the postgress to pgadmin.  <br> <br> 

pgadmin username: admin@admin.com  <br> 
pgadmin password: admin  <br> 
pgadmin port: 8080  <br> 

postgress username: admin  <br> 
postgress password: admin  <br> 
postgress port: 5432  <br> 

postgress use ./data directory as persistent storage <br>

project-folder/ <br>
├──docker-compose.yml <br>
├── servers.json <br>
└── data/          <-- This will be created automatically by Docker
