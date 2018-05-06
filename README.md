# hackerspace + Docker + LinuxServer.io = <3

## Pull the image

    docker pull bashninja/docker-hackerspace

## Run the Django Hackerspace Application

    docker run -d \
        -v {path}:/config \
        -p 80:8181/tcp \
        bashninja/docker-hackerspace

## Configure the Django Hackerspace Application

* Open your {path} for `/config` and edit `settings.py` file
* Fill with your API and other Keys
* Fun
