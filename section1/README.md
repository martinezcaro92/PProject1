# Section1 commands to build
Open a new terminal in section1 directory and build the Dockerfile:
> docker build -t section1-image .

After build it, you should run the builded container
> docker rm -f section1-container && docker run -p 3000:3000 -dit --name=section1-container section1-container

