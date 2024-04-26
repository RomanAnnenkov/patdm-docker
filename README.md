# patdm-docker
This is a project for deploy the patdm service in docker using docker-compose.
For successful deployment you need to place the patdm-site and patdm-converter repository in this directory, and create directories **storage** and **logs**.

Comand for create directories:

`mkdir -p logs/nginx logs/converter logs/site storage` 

Command for clone repositories by ssh:

`git clone git@github.com:RomanAnnenkov/patdm-converter.git`
`git clone git@github.com:RomanAnnenkov/patdm-site.git`

Command for build and deploy service :

`docker-compose up -d --build`
