# Nginx Project

## Introduction
This Project includes two webpages,
1. Test Webpage (Run it on linux)
2. My portfolio (Run it on Docker Container)

## Steps to start :

### Created index.html inside /var/www/html it shows Test webpage. 
#### Execute command using : 
```./install_nginx.sh```

### Created Dockerfile of run my portfolio.
#### Create image :
```docker build -t devops-nginx-demo .```
#### Create Contianer :
```docker run -d -p 80:80 devops-nginx-demo:latest```

