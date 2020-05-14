# nodejs14_debian
A Debian Dockerfile with installed NodeJS 14

if you want to mount your own folder (for examlpe for scripts) you can mount 

```/opt/userscripts```

For Example:

```docker run -d --name nodejs14_debian -v /your/folder:/opt/userscripts mcdhrts/nodejs14_debian:latest```
