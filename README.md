
# DockerJup-Lab: Jupiter-lab on Docker 

With this repository I will show you how to deploy Jupiter-lab on Docker. Already ready-to-run Docker images containing Jupiter applications and interactive computing tools exist as you an see in the [Jupiter-docker-stack GitHub repository](https://github.com/jupyter/docker-stacks) (created and maintained by the official Jupiter team).

## Fast way to download the image and run the project

```
docker run -d -v "/${PWD}/Notebook:/SRC/Notebook" --name "dockjup-lab" -p 8888:8888 --restart always --shm-size 2g sicilian4ever/dockjup-lab
```
Then access the following web page: **localhost:8888**


**However what if we are not satisfied with these images ready-to-run and we what to have one tailored to our needs?**

After log-in to your personal space (Password=sicilian4ever):

<center>
    <img width="800" alt="pwd" src="DOC/pwd.png" style="border: 5px solid black">
</center>

You will able to access your Jupiter-lab working space:

<center>
    <img width="800" alt="Screenshot" src="DOC/Screenshot.png" style="border: 5px solid black">
</center>

**The Docker image of this project can be found in the official Docker registry accessible by using the link below:**

[https://hub.docker.com/r/sicilian4ever/dockjup-lab](https://hub.docker.com/r/sicilian4ever/dockjup-lab)


Have fun!! :)
