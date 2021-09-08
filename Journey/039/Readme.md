# Creating a Production-Grade Workflow #3

## Cloud Research
- Today, I've setuped a final part of an exercise creating a production-grade workflow. The website will be run on Nginx web server, so we create a multi-step Dockerfile to achieve that.

## __Starting Commands__
1. Build an image from the project
```sh
cd react-app
docker build -t 100dayofcloud/simple-react-produciton .
```

2. Run Nginx webserver
```sh
docker run -p 8080:80 100dayofcloud/simple-react-produciton
```

After execute the second command, you should be able to visit the website at [http://localhost:8080](http://localhost:8080/)

## Social Proof
I'm not going to post my progression on social media.