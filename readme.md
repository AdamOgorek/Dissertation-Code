# HTTP/3 in Kubernetes
This repository contains the code I wrote or adapted for use in my dissertation.

# Folders
The Aioquic folder contains the deployment and service YAML files used to deploy those in Kubernets for testing. The Aioquic GitHub repository containing the client and server code can be found [here](https://github.com/aiortc/aioquic/).

docker-nginx-http3 folder contains the code adapted to test out HTTP/3 multiplexing capabilities of an Nginx server. Most of the code is taken from [macbre's repository](https://github.com/macbre/docker-nginx-http3/).
I changed the index.html file in the tests folder, added resources to be served by the website and modified https.conf file to allow HTTP/3 multiplexing.

