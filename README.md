# Docker
Cloud Project 1: Docker and Web Services
<p>The generated docker image contains all the required environment setup as well as the weather forecast application that gives the maximum and minimum temperature for a range of dates.It also has the API methods for various GET,POST,DELETE methods.
  
<p><b>Docker Installation:</b><p>
<p>Follow these commands in sequence in the AWS ubuntu instance<p>
<p>sudo apt install apt-transport-https ca-certificates curl software-properties-common
<p>curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
<p>sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu bionic stable"
<p>sudo apt install docker-ce

<p><b>Steps to create our own image </b></p>
<p>Sign up for Docker hub account https://hub.docker.com
<p>Search for base docker and pull it
<p>Run docker container with downloaded image
<p>Create the base image
<p>Create a dockerfile for generating our image
<p>Build docker image
<p>Test the image and commit back to repository for reuse

<p><b>How to use</b>
<p>Import the .tgz file using Docker import. Give the command:

<p>docker run -d -p 8081:80 yourdockername

<p>This will get the service started. Once that is done, go to the web browser and give: localhost:8080/historical


