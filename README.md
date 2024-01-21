# Calculator-githubAction
A simple calculator project in java
Github action would first build using maven
Github action will then build the docker image and push it to docker hub
Github action will then run the ansible playbook which will deploy the image on the host provided in the inventory
