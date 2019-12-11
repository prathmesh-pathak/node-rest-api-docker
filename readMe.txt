This project was created using node js.

There is a file called package.json that has dependecies 

Goto the project folder in cmd run npm install it will install the dependecies.

next start the docker toolbox from this link https://github.com/docker/toolbox/releases

download the .exe file. install the file. make sure you have the latest virtualbox version.

Start the toolbox.

Now, navigate to your project folder and in cmd run the following set of commands.

docker build -t <image-name>

docker run -d -p 1200:1200 <image name>

docker ps

docker logs <container id>

Now th docker setup has been completed.

There are three ways to run the project:

1) By going to localhost:1200 

2) By going to 0.0.0.0:1200

3) Go to your toolbox console there will message saying "docker is configured to use the default machine with IP 192.168.99.100"
go to this link 192.168.99.100:1200

Thats it that's how you run a node prject in docker


