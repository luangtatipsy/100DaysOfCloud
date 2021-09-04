# Making Real Projects with Docker

## Cloud Research
- Today, I've learned about how to create a real project. This exercise I create a simple web application with NodeJS.

## __Starting Commands__
1. Build an image from the project
```sh
cd src
docker build -t 100dayofcloud/simple-web .
```

2. Run web server
```sh
docker run -p 8080:8080 100dayofcloud/simple-web
```
After execute the second command, you should be able to visit the website at [http://localhost:8080](http://localhost:8080/)

## Social Proof
I'm not going to post my progression on social media.