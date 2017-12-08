# Building Sample LAMP stack with docker-compose

## Usage
- Start `docker-compose up -d`
- Open "http://localhost/"
- Edit `var/public_html/`
- SSH `docker exec -it lampsample_web01_1 bash`
- Stop `docker-compose stop`
- List stopped container `docker ps -a`
- List all images `docker images`
- Remove container `docker rm CONTAINER_ID`
- Remove image `docker rmi IMAGE_ID`
