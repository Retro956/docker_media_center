# docker_media_center

I just decided to put my docker-compose.yml file up here to keep track 
of the changes I add.  Typically, I do not update this very often.

## Current Issues

It looks like watchtower is not working properly.  I will have to take a 
look at this when I have a minute.

## Setup

Be sure to take a look at the docker-compose.yml file.  In there, you 
will see a few of my .env variables.  You can either add your own 
variables here or you can create your own .env file and map those.

After that, just run "sudo docker-compose pull && sudo docker-compose up -d" 
and off you go.
