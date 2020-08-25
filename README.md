### Pushing an image to Docker

1) Firstly, create a repo on Docker Hub.


2) Let's push an image of NGINX to our repo. Create the image with the following command:

`docker run -d -p 80:80 nginx`


3) Run `docker ps` to identify the image ID.


4) Tag this to your Docker repo using the following command:

`docker tag 4bb46517cac3 medimidi/docker_mehdi:First_Commit`

The string of numbers above is your Image ID. The message after the colon is your commit message.


5) Finally, push the image to your repo using the push command:

`docker push medimidi/docker_mehdi`
