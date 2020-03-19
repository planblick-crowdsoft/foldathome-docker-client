# foldathome-docker-client
This container is a ready2run Fold@Home client for server systems. Therefor GPU support is disabled. 

Just run the container and the client will automatically be started and asks for tasks from Fold@Home:
https://foldingathome.org/2020/03/15/coronavirus-what-were-doing-and-how-you-can-help-in-simple-terms/

In our Github repository we provide a docker-compose and an Openshift-deployment-config to run this or just use:

`docker run planblick2/foldathome`

By default, you'll join the crowdsoft team on Fold@Home and the container uses "Crowdsoft-Docker-Image" as Fold@Home user. 
You can change this in the Dockerfile. 
