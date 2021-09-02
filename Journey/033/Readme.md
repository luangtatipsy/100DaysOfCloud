# Building Your Own Docker Image

## Cloud Research
- Today, I've learned about how to create a custom Docker image.

Building an image comprises 3 following steps: specify instructions in a Dockerfile, execute Docker cli, and take a snapshot to Docker Deamon. By performing those steps results you a usable Docker image.

<div align="center"><img src="diagrams-01 - dockerfile.png" alt="" /></div>

Let's dig down into detail, we need to specify a base image that is similar to install an operating system on your own computer. Secondly, we need to specify commands which we need to run for preparing this image. Lastly, we need to specify a primary command to run on container startup.

<div align="center"><img src="diagrams-02 - base.png" alt="" /></div>

For instructions, there is reserved words telling Docker what to do for each command (argument after the instruction). Docker execute an instruction one by one, creating a temporary container and take a snapshot for each row of instructions. The last one is the usable image store in your machine.

<div align="center"><img src="diagrams-03 - instruction.png" alt="" /></div>

To be more clear, the diagram below shows all of the hidden steps for each instruction.

<div align="center"><img src="diagrams-04 - process.png" alt="" /></div>

## Social Proof
I'm not going to post my progression on social media.
