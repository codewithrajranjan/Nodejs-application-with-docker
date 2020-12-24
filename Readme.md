# Sample nodejs application with docker Conatiners


# Installation


```javascript

    // clone the application with git clone

    // then install the npm modules using
     
    npm install


```


# Running the applications


```javascript


    node server.js


```


# Building docker image

```bash

    docker build -t <imagename:version> .

```



# Running docker container


```bash

    // 9005 port is given since the docker file contains 9005 port
    docker run -it -d -p <outside-port-of-your-choice>:9005 <imagename:version>

```


