
jenkins/jenkins:lts with docker command support 


#How to use this image

    docker run -p 8080:8080 -p 50000:50000 -v /var/jenkins_home -v /var/run/docker.sock:/var/run/docker.sock tasanakorn/jenkins-docker