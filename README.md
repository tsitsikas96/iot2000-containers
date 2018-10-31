# iot2000-containers
Containers integration for IOT2000

To run the build open terminal and write the following:
docker run -v $(pwd):/shared-volume:rw -e USER_ID=$(id -u) -it kasproject/kas:latest

Inside the container go to /shared-folder directory and write:
kas build meta-virtualization/kas.yml
