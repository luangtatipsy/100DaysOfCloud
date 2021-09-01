# Executing Commands in Running Containers

## Cloud Research
- Today, I've learned about how to executing commands in running containers using docker `exec` which allows a given command in a container environment. 

<img src="diagrams-01 - exec.png" width="1024px" alt="" />

Docker `exec` stands for execute which allows you run a new command in a running container. The important thing is arguments `-i`, and `-t`, these arguments allow us to provide an input and return its output back to a terminal screen.

<img src="diagrams-02 - stdin.png" width="1024px" alt="" />

without `-it` arguments, the process will neither allow nor return to the terminal screen.


## Social Proof
I'm not going to post my progression on social media.
