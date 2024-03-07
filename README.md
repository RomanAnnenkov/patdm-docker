# patdm-docker
This is a project for deploy the patdm service in docker using docker-compose.
For successful deployment you need to place the patdm-site and patdm-converter repository in this directory, and create directories **storage** and **logs**.

Comand for create directories:

`mkdir -p logs/nginx logs/converter logs/site storage`

Command for deploy service :

`docker-compose up -d`
