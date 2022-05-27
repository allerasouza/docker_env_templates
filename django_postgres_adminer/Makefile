clean:
		git reset --hard
		git clean -fxd

startproject:
		docker-compose run web django-admin startproject $(project_name) .

up:
	    docker-compose up -d

down:
		docker-compose down
