# iot2000-containers
Containers integration for IOT2000

Move the kas.yml file outside of iot2000-containers folder and then

docker run -v $(pwd):/shared-volume:rw -e USER_ID=$(id -u) -it --rm kasproject/kas:latest

Inside the container go to /shared-folder directory and write:

kas build kas.yml
