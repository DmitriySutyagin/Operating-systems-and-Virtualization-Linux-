# Lesson 6. Starting a stack for a Web application

* Install Nginx and configure it to work with PHP-FPM.

* Install Apache. Configure PHP processing. To achieve simultaneous work with Nginx.

* Configure the reverse proxy scheme for Nginx (dynamics - on Apache).

![Screenshot](/ScreenShot/Screenshot_config_parts_2.png)
![Screenshot](/ScreenShot/Screenshot_config.png)
![Screenshot](/ScreenShot/lESSON_6.%20localhost_image.png)

* Install MySQL. Create a new database and a table in it.

![Screenshot](/ScreenShot/Lesson_6.%20DATABASE.png)

* Install the phpmyadmin package and run its web interface for MySQL management.

![Screenshot](/ScreenShot/phpmyadmin.png)

* Configure the traffic balancing scheme between several Apache servers on the Nginx side using the ngx_http_upstream_module module.

![Screenshot](/ScreenShot/ngx_http_upstream_module.png)