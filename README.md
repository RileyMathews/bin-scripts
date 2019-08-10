# Scripts

## docker-here
takes an argument of an accessible docker image you would want to run. It creates a temporary image from that parent image with a /workspaces directory, then runs that image while mounting in your current directory into the /workspaces directory.