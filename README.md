# ssignage-bk-container



##### tar -xzvf docker_backup.tar.gz
##### docker load -i exported_images/*.tar
##### cat exported_containers/*.tar | while read container; do docker import "$container"; done
