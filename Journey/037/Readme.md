# Creating a Production-Grade Workflow #1

## Cloud Research
- Today, I've setuped a part of an exercise creating a production-grade workflow. According to the environment of NodeJS, commands for running in development, and production environments are different so we should separate Dockerfile out for executing 2 different primary commands.

## __Starting Commands__
1. Build an image from the project
```sh
cd react-app
docker build -t 100dayofcloud/simple-react-produciton -f Dockerfile.dev .
```

2. Run web server
```sh
docker run -it -p 3000:3000 -it 100dayofcloud/simple-react-produciton
```
After execute the second command, you should be able to visit the website at [http://localhost:3000](http://localhost:3000/)

## Social Proof
I'm not going to post my progression on social media.