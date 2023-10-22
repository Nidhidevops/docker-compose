# docker-compose

## TIPS
Docker compose
: tool for defining & running multi-container docker applications
: use yaml files to configure application services (docker-compose.yml)
: can start all services with a single command : docker compose up
: can stop all services with a single command : docker compose down
: can scale up selected services when required

Step 1 : install docker compose
   (already installed on windows and mac with docker)
   docker-compose -v
   
   2 Ways

   1.  https://github.com/docker/compose/rel...

   2. Using PIP
    pip install -U docker-compose

Step 2 : Create docker compose file at any location on your system
   docker-compose.yml

Step 3 : Check the validity of file by command
    docker-compose config

Step 4 : Run docker-compose.yml file by command
   docker-compose up -d

Steps 5 : Bring down application by command
   docker-compose down

![image](https://github.com/Nidhidevops/docker-compose/assets/140115299/e4743b71-7f77-47f0-b9e1-0f90e5fadca7)

![image](https://github.com/Nidhidevops/docker-compose/assets/140115299/da7b230e-676a-43bb-a1de-9b0512b8f4fa)
