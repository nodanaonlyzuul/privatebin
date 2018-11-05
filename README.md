# ZeroBin

It's bad to send credentials via Slack & Email.  
Source: jgeusebroek/zerobin [Dockerhub](https://hub.docker.com/r/jgeusebroek/zerobin/)/[Github](https://github.com/jgeusebroek/docker-zerobin)

## Running Locally

`docker-compose up`

## Running on ECS

### Security

This should only be run:

1.  Over HTTPS.
2.  In a way that it's not accessible to the outside world.
What good is a private pastebin if Slackbot can read it for a preview?