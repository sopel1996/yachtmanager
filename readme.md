# Yacht work manager

Web application for accounting work on a yacht

## Installation
#### NGINX Setup
![NIGNX](https://img.shields.io/badge/Nginx-009639?logo=nginx&logoColor=white&style=for-the-badge)

Install nginx

```
sudo apt update
sudo apt install nginx
```
Install ufw and allow NGINX

```
sudo apt install ufw
sudo ufw allow 'Nginx Full'
```

Upload config from .nginx
> `default` in sites-available
> `nginx.conf` in nginx root

Install certbot and install SSL
```
sudo apt install certbot python3-certbot-nginx
sudo certbot --nginx
```
Restart nginx
```
sudo service nginx restart
```
#### submodules
initial and update submodules
```
git submodule init
git submodule update
```
submodules list

[yachtClient](https://github.com/sopel1996/yachtClient)   ![REACT](https://shields.io/badge/react-black?logo=react&style=for-the-badge&height=30)

[yachtServer](https://github.com/sopel1996/yachtServer) ![NodeJS](https://img.shields.io/badge/Node.js-339933?logo=Node.js&logoColor=white&height=30)
