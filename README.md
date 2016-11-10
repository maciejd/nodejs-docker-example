# nodejs-docker-example
### Build and run docker container with Node.js web app

Clone repo `git clone https://github.com/maciejd/nodejs-docker-example.git`

Chande directory `cd nodejs-docker-example`

Build image `docker build -t node-web-app .` 
  
Run container in detached mode and publish port 8080 `docker run -d -p 8080:8080 node-web-app`
  
App should be accessible on port 8080 `curl -i localhost:8080`
