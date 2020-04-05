# Hit Counter App

## Components

There are two components Flask application and Redis as datastore.

## Functionality

The working of architecture is very simple, when you hit the url of frontend the flask app will show the number of times the page was visited. The count of visits is stored in Redis. So when you visit the page, the Flask web app will update the entry in the Redis.

## Kubernetes Components

- Redis Deployment
- Redis Service
- App Deployment
- App Service

## To Run Setup Locally

This will download Docker images from dockerhub

```bash
bash start.sh
```
