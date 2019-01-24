A Sample Code for Docker Swarm Clustering Demo.

1. Clone the Repository to your Linux machine

2. run ls command
The ls command should now show the myswarmapp directory in current location

3. cd to the myswarmapp directory

4. run the below command to create a Dockerfile from app.py python application
docker image build -t myswarmapp:1.0.0 .

5. Create a Swarm Cluster and run the below command
docker stack deplpy -c docker-compose.yml demoapp-1
