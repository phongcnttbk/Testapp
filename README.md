#Requirement
	- Docker
	- Docker-compose

Run
	docker-compose up -d
	docker-compose logs -f >> /var/log/testapp.log

Next step:
	Provision application with ansible
	Install rsyslog to docker hosts and use syslog drive to centralize log Testapp
