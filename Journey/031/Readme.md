# Docker Life Cycle

## Cloud Research
- Today, I've learned about Docker life cycle, and how to override command for running a container.

Creating and running a container from an image. It can be simply run it by provide an image name however, a default command can be overrided as the following figure showed below.

<img src="diagrams-01 - override.png" width="1024px" alt="" />

For more detail, docker `run` command is a combination between `create` and `start`.

<img src="diagrams-02 - run.png" width="1024px" alt="" />

<img src="diagrams-03 - create.png" width="1024px" alt="" />

For docker `create` it simply create a container with a given image and return its id whereas docker `start` is an execute command for running a given container id.

<img src="diagrams-04 - stop kill.png" width="1024px" alt="" />

Lastly, running containers should be stopped or killed when they are not be necessarily used. Docker `stop` is a command to stop a running process but, not delete it, it can be started again later. On the other hand, docker `kill` command is a command to stop and eliminate a running process both. In order to the container, it has to be created from the image again.

## Social Proof
I'm not going to post my progression on social media.
