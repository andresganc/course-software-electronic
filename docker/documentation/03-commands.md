
## MOST COMMON COMMANDS

    - This are the most common command


### $ docker run

### $ docker pull

### $ docker images




### docker run 

    - docker run is used to run and pull the images

    $ docker run

    Examples: 

        $ docker run my-postgres

        $ docker run -e POSTGRES_PASSWORD=123456 postgres

        $ docker run -d my-postgres

            - Run container background


### docker pull

    - docker pull download the images

    $ docker pull

    Examples:

    $ docker pull ubuntu


### docker images

    - docker images show the images downloads

    $ docker images

    Examples: 

        $ docker images

            - show all images

        $ docker images -a

            - List all images

        $ docker images | head



### docker ps

    - docker ps show the images running

    $ docker ps

    Examples

    $ docker ps

    $ docker ps -a

        - show the images that ran



### docker start

    - docker start - Start an image

    $ docker start ID

    $ docker start NAME

    Examples

    $ docker start f2a0f7a79bd

    $ docker start my-postgres


### docker logs 

    - docker logs show the logs of the image that is running

    $ docker logs ID

    $ docker logs NAME

    Examples

    $ docker logs f2a0f7a79bd

    $ docker logs my-postgres

    $ docker logs -f f2a0f7a79bd

        - show the logs step by step

    $ docker logs -f my-postgres

        - show the logs step by step


### docker exec

    - docker exec 
        - Execute a command inside a container that is already running
        - Ejecuta un comando dentro de un contenedor que ya esta corriendo

    $ docker exec ID

    $ docker exec NAME

    Examples 

    $ docker exec -it f2a0f7a79bd sh

    $ docker exec -it my-postgres sh


### docker stop

    - docker stop

        - docker stop - Stop an image

    $ docker stop ID

    $ docker stop NAME

    Examples

    $ docker stop f2a0f7a79bd

    $ docker stop my-postgres

    $ docker stop f2a0f7a79bd 64f7d5c22730

        - stop various containers at the time

    

