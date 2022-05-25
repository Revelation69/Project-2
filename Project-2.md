# DOCUMENTATION OF PROJECT 2: LEMP STACK IMPLEMENTATION

## INSTALLATION OF NGINX WEB SERVER

- Installed NGINX using 'apt' package manager:

`sudo apt update`

`sudo aot install nginx`

- Verified that the nginx is running as a service in my OS

`sudo systemctl status nginx`

-Accessed the server locally via my OS

`curl http://localhost:80`

![Server locally accessed via OS Result](images/Accessed-server-locally.png)

- Accessed the server via internet to ensure it's perfectly working

	[Server-accessed- via-internet](https://54.212.107.146)

	![Server-accessed- via-internet Result](images/server-accessed-via-internet.png)

## Installation of MYSQL to store and manage my site data

- Installed MYSQL using 'apt' package manager:

`sudo apt install mysql-server`
`sudo mysql`

## Installation of php for processing code to display dynamic content to end user

- Installed PHP-FPM and PHP-MYSQL using 'apt' package manager:


`sudo apt install php-fpm php-mysql`


