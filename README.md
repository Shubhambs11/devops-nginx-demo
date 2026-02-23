# DevOps Nginx Test

## Intro 
This project helps to install nginx on linux and Docker Container

## Steps to start :

### Create index.html inside /var/www/html it shows test website. 
#### Execute command using : 
```./install_nginx.sh```

### Created Dockerfile
#### Create image :
```docker build -t devops-nginx-demo .```
#### Create Contianer :
```docker run -d -p 80:80 devops-nginx-demo:latest```

