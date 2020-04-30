
# Run Jenkins & Sonar Docker Containers
- Make sure docker daemon is running before going to next step
- Run `docker-compose up` command. 
- After 5 mins wait, your Jenkins & SonarQube should be up 
- Access both server with following URLs:
- Jenkins - http://localhost:8080
- SonarQube - http://localhost:9000


## Tips
- To See Jenkins Password run 'Docker logs <JenkinsContainerID>
- Docker PS - will list containers
