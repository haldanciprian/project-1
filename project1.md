## Documentation of project 1

### Web stack implementation in AWS - LAMP (Linux, Apache, MySQL, PHP or Python, or Perl)

In order to complete this project you will need an AWS account and a virtual server with Ubuntu Server OS.

**Connect with PEM file**

![Connect with PEM file](./images/EC2_connect_with_pem.png)

**Install apache**

```
#update a list of packages in package manager
sudo apt update

#run apache2 package installation
sudo apt install apache2
```

## To verify that apache2 is running as a Service in our OS, use following command

```
sudo systemctl status apache2
```

![Apache status](./images/apache-status.png)

[Install openssh](https://learn.microsoft.com/en-us/windows-server/administration/openssh/openssh_install_firstuse?tabs=powershell#install-openssh-for-windows)

[OpenSSH key management](https://learn.microsoft.com/en-us/windows-server/administration/openssh/openssh_keymanagement)

**Connect with openSSH**

![Connect with openSSH](./images/EC2_connect_with_openSSH.png)

**Accessing Apache from internet**

![Accesing Apache](./images/Accessing_apache_fromInternet.png)

**Install mysql server**

```
sudo apt install mysql-server
```

**Mysql status**

![Mysql status](./images/mysql-status.png)

**Accessing mysql**

![Mysql status](./images/accessing_mysql.png)


**Install php**

```
sudo apt install php libapache2-mod-php php-mysql
```

**Php version**

![Mysql status](./images/php_version.png)

**Result**

![result](./images/result.png)