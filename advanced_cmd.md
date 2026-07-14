##run image
docker run -it <image_name>
docker run -it --rm <image_name>

##container manipulation
docker start <container_id>
docker start -ai <container_id>
docker stop <container_id>

##while container is up
docker exec -it <container_id> bash
docker exec <container_id> <any_valid_linux_command>
