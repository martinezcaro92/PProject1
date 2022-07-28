# Section1 commands to build
Open a new terminal in section1 directory and build the Dockerfile:
> docker build -t section2-image .

After build it, you should run the builded container
> docker rm -f section2-container && docker run -p 80:80 -dit --name=section2-container section2-image

