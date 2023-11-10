## Docker Basics Tasks
1. Open Visual Studio Code & install the WSL extensions and Docker extension in the Visual Studio Code.
![Alt Text](screenshots/wsl.png)
![Alt Text](screenshots/vs_docker.png)

2. Do the following tasks using Visual Studio Code:

    i. Use Docker run command to run a docker container based on hello-world image
    ![Alt Text](screenshots/hello.png)

    ii. Use Docker run command to run a docker container based on alpine image
    ![Alt Text](screenshots/alpine.png)

    iii.Use Docker run command to run a docker container based on alpine image and get access to the container shell.

        a.Use mkdir command to make some directories.

        b.Use exit command to exit from the container’s shell.
    
    ![Alt Text](screenshots/alpine_cmd.png)

    iv. Run a static website in a container using an existing image “static-site”.
        a. docker run --name static-site-2 -e AUTHOR="Your Name" -d -p 8888:80 dockersamples/static-site
        ![Alt Text](screenshots/site.png)

        b.Type localhost:8888 in your browser.
    ![Alt Text](screenshots/8888.png)

    v. List all containers that are currently running in your system
    ![Alt Text](screenshots/docker_ps.png)

    vi. List all containers both running & the ones that are stopped
    ![Alt Text](screenshots/docker_ps_a.png)

    vii. Stop one of your running containers.
    ![Alt Text](screenshots/docker_stop.png)

     9 Remove one of your containers.
    ![Alt Text](screenshots/docker_rm.png)