
# docker-youtrack

*Easy youtrack deployment using docker*

These Dockerfiles allow you to easily build images to deploy your own [youtrack](http://www.jetbrains.com/youtrack/) instance.
It's free for up to ten users.

## Disclaimer
Besides that, as always, use these scripts with care.

Don't forget to back up your data very often, too.

## Requirements
Docker has to run. It supports many platforms like Ubuntu, Arch Linux, Mac OS X, Windows, EC2 or the Google Cloud.
[Click here](http://docs.docker.io/en/latest/installation/) to get specific infos on how to install on your platform.

You also need some RAM for youtrack, but I can't really tell how much. Maybe about 200-300MB.

## Oh nice! How do I do it?
1. Install docker. [It's not very hard.](http://docs.docker.io/en/latest/installation/)
2. Run it! (Stop with CTRL-C, repeat at pleasure)

  `docker run -p 8080:8080 --volume /your-youtrack-data:/youtrack-data remmelt/youtrack`

Now open your browser and point it to http://localhost:8080 and rejoice.
