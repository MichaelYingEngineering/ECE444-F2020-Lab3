# ECE444-F2020-Lab4&5

# Michael Ying
Referenced from https://codefresh.io/docker-tutorial/hello-whale-getting-started-docker-flask/

[ss1]: DockerfileLocation.PNG "Dockerfile Location"
[ss2]: DockerBuildCommand.PNG "Docker Build"
[ss3]: DockerRunCommand.PNG "Docker Run"
[ss4]: DockerImage.PNG "Docker Image"
[ss5]: DockerContainer.PNG "Docker Container"
[ss6]: Browser.PNG "Browser"

# Activity 1
Perform all development in a branch "lab4_Microservice_Experiment" in your Lab3 task GitHub repository (you are experimenting after all).
# Activity 2
Steps to build and start the system:
1. Clone this git repo and go to its location. The Dockerfile can be found there.
![alt text][ss1]
2. Run the command **docker build -t ece444-f2020-lab3 .** to build image
![alt text][ss2]
3. Run the container using command **docker run -d -p 5000:5000 ece444-f2020-lab3**
![alt text][ss3]

- Screenshot of browser
![alt text][ss6]
- Docker image and container
![alt text][ss4]
![alt text][ss5]

**Miscellaneous Commands**:
- **docker image ls** - List images
- **docker ps -a** - List containers
- **docker image rm (ID)** - Remove images
- **docker container stop (ID)** - Stop containers
- **docker container rm (ID)** - Remove containers

# Activity 3
Briefly summarize the differences between Docker and Virtual Machine: