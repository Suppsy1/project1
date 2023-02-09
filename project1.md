# Project 1
## Installing apache and updating the firewall

`sudo apt update` to update all the list of packages ![Sudo Apt Updste](./images/sudoapp.PNG)

`sudo apt instal apache2` to install the apache package ![Installing Apache](./images/install_apache2.1.PNG)

`sudo systemctl status apache2 ` to confrim if the apache is running as a service in our operating system ![Apache Status](./images/Apache-status.PNG)

`local host and public adress` To access the server locally and also test how our Apache HTTP server can respond to requests from the Internet ![Public Address](./images/curl-on-terminal.PNG)

On web ![public Address](./images/curl-on-web.PNG)

## Installing mysql

`sudo apt install mysql-serve` to acquire and install mysql server ![Mysql Server](./images/installing-msql.PNG) 

`sudo mysql` to login into MYSQL console ![Login](./images/logging%20in%20mysql.PNG)

`ALTER USER 'root'@'localhost' IDENTIFIED WITH mysql_native_password BY 'PassWord.1';` setting default password ![default password](./images/change%20msql%20password.PNG)

`sudo mysql_secure_installation` Changing the default password ![default password](./images/change-password.PNG)
