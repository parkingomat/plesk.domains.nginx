# plesk.domains.nginx
Environment for nginx server to start php app


[How To Install Linux, Nginx, MySQL, PHP (LEMP stack) on Ubuntu 18.04 | DigitalOcean](https://www.digitalocean.com/community/tutorials/how-to-install-linux-nginx-mysql-php-lemp-stack-ubuntu-18-04)

> ## Installing the Nginx Web Server
> 
> In order to display web pages to our site visitors, we are going to employ Nginx, a modern, efficient web server.
> 
> All of the software used in this procedure will come from Ubuntu’s default package repositories. This means we can use the `apt` package management suite to complete the necessary installations.
> 
> Since this is our first time using `apt` for this session, start off by updating your server’s package index. Following that, install the server:
> 
>     sudo apt update
>     sudo apt install nginx
>     
> 
>  
> 
> On Ubuntu 18.04, Nginx is configured to start running upon installation.
> 
> If you have the `ufw` firewall running, as outlined in the initial setup guide, you will need to allow connections to Nginx. Nginx registers itself with `ufw` upon installation, so the procedure is rather straightforward.
> 
> It is recommended that you enable the most restrictive profile that will still allow the traffic you want. Since you haven’t configured SSL for your server in this guide, you will only need to allow traffic on port `80`.
> 
> Enable this by typing:
> 
>     sudo ufw allow 'Nginx HTTP'
>     
> 
>  
> 
> You can verify the change by running:
> 
>     sudo ufw status
>     
> 
>  
> 
> This command’s output will show that HTTP traffic is allowed:


https://www.digitalocean.com/community/tutorials/how-to-install-linux-nginx-mysql-php-lemp-stack-ubuntu-18-04
