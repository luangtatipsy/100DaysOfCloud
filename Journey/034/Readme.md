# Manual Image Generation with Docker Commit

## Cloud Research
- Today, I've learned about Docker `commit` which is a command creating a new image from a container’s changes.

## __Docker Commit__
It can be useful to commit a container’s file changes or settings into a new image. This allows you to debug a container by running an interactive shell, or to export a working dataset to another server. Generally, it is better to use Dockerfiles to manage your images in a documented and maintainable way.

The commit operation will not include any data contained in volumes mounted inside the container.

By default, the container being committed and its processes will be paused while the image is committed. This reduces the likelihood of encountering data corruption during the process of creating the commit. If this behavior is undesired, set the `--pause` option to false.

The `--change` option will apply `Dockerfile` instructions to the image that is created. Supported `Dockerfile` instructions: `CMD` | `ENTRYPOINT` | `ENV` | `EXPOSE` | `LABEL` | `ONBUILD` | `USER` | `VOLUME` | `WORKDIR`

## Social Proof
I'm not going to post my progression on social media.
