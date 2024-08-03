Step 1: Create the Flask Application
 First, create a directory for your project and navigate into it. Inside this directory, create a file called app.py 
Step 2: Create a Requirements File
Create a requirements.txt file to list the dependencies for your Flask application
Step 3: Create a Dockerfile
Create a Dockerfile to specify how the Docker image should be built
Step 4: Create a Docker Compose File
Create a docker-compose.yml file to define and run multi-container Docker applications:

Commands:
sudo docker build -t dockerimage .        //To create docker image out of docker file
sudo docker run --name dockercontainer dockerimage  //To create Container out of Docker Image
Sudo docker ps                      //To check Running Containers
Sudo docker ps -a                //To check all list of Containers

docker compose up –build
