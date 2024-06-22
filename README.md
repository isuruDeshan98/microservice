# microservice

First run registry-compose.yml for config the private registry service inside swarm cluster
  "docker stack deploy -c registry-compose.yml my_reg"

Then build the images using docker-compose.yaml
  "docker compose -f docker-compose.yaml build"

Then push the images to created registry service using docker-compose.yaml
  "docker compose -f docker-compose.yaml push"

 Run this command to make sure wait-for-eureka.sh has execution permissions(This is for hold the current service untill dependent services available)
  chmod +x wait-for-eureka.sh

Finally run the docker-compose.yaml to deploy the stack(environmrnt variable should change with stack name)
  "docker stack deploy -c docker-compose.yaml microservice"

**************Note***************** 
If your using one docker node without swarm. Use compose.yaml
  "docker compose -f compose.yaml up -d"

  
