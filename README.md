# tradura-compose

[Ever® Traduora](https://docs.traduora.co/) is an Open-Source Translation Management Platform, and this repo is simply a docker compose
file that you can use to run it locally for testing, or to see how the configurations would need to be set
up. Please don't run this in production without actual secrets and real passwords. 



## Run container

This is a simple setup with the DB in the same compose file, this is mostly to test the platform or see how it works. You would need a real DB to keep using it.

To start, run the docker compose:

    docker compose -f tradura-compose.yml up

Once the logs show 'listening' you can then open the app, register and create an account to get started. 

Link to open the local running instance: [http://0.0.0.0:8080/](http://0.0.0.0:8080/)


