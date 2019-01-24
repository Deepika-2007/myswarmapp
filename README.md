A Sample Code for Docker Swarm Clustering Demo.

Clone the Repository to your Linux machine

ls
The ls command should now show the myswarmapp directory in current location

cd to the myswarmapp directory

run the below command to create a Dockerfile from app.py python application
docker image build -t myswarmapp:1.0.0 .

Create a Swarm Cluster and run the below command
docker stack deplpy -c docker-compose.yml demoapp-1
