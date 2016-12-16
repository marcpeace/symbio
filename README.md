# symbio
Test of wordpress/docker containers
The docker development environment is built from two docker containers.
The first container is a nginx/php server, the second a mariaDb container, which are linked via a docker-compose file.
Wordpress has been installed on this environment and is used for a custom plugin.
The plugin allows for a character search using the stawards api SWAPI.
