Synology Docker OpenHAB 2
====================

This is my `docker-compose` suite for deploying OpenHAB 2 and a few other services on Synology Diskstation. 

I'm trying to create a pure file based config of my running OpenHAB 2 container to be able to restore it if i crash it with some experiments ;-)

## Install

Git-clone this repository on Diskstation, e.g. into `/volume1/docker`.

Then start all containers by executing:

	docker-compose up -d

## Update

	docker-compose pull
	docker-compose down
	docker-compose up -d