# docker

Run with attached volume using current directory and mapped port:

For Linux
    
    docker run -it -p 8888:8888 -v $(pwd):/app --name [name] repo/image bash

For Windows

    docker run -it -p 8888:8888 -v ${pwd}:/app --name [name] repo/image bash

Restart container and attach
    
    docker start dpsim-dev
    docker attach dpsim-dev
    
Attach second shell to container

    docker exec -ti dpsim-dev bash
