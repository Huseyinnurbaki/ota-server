https://hub.docker.com/_/mariadb
http://www.electrode.io/docs/what_is_electrode.html


mariadb

$ docker run --name some-mariadb -e MYSQL_ROOT_PASSWORD=my-secret-pw -d mariadb:tag
docker-compose -f stack.yml up