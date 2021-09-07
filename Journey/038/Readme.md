# Creating a Production-Grade Workflow #1

## Cloud Research
- Today, I've setuped a part of an exercise creating a production-grade workflow. In order to make docker automatically refresh source code when we edited any code on our local machine, we need to map volumes on our local machine to the container project directory.

## __Starting Commands__
1. Build an image from the project
```sh
cd react-app
docker compose up --build
```

After execute the second command, you should be able to visit the website at [http://localhost:3000](http://localhost:3000/)

## Social Proof
I'm not going to post my progression on social media.