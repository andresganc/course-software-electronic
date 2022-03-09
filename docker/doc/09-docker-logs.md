
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