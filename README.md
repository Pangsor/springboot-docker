# springboot-docker

Maven -> springboot-docker -> Lifecycle -> clean and package -> Run Maven Build
* docker build -t springboot-docker . 
* docker images 
* docker build -t springboot-docker:0.1.RELEASE .
* docker images
* docker run -p 8080:8080 springboot-docker
* docker ps

# Push docker image to docker hub

* docker login
* docker tag springboot-docker pangsor/springboot-docker:0.1.RELEASE
* docker push pangsor/springboot-docker:0.1.RELEASE