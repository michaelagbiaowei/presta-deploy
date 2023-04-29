## **How to install and setup Prestashop on AWS**

![image](./assests/image.jpg)

PrestaShop is an open-source E-Commence platform that is free to use. It is one of the most popular E-Commence website builder platforms and has an intuitive interface that makes it easy to manage your online store.

PrestaShop is easy to use and offers a responsive store interface for shoppers. Prestashop It provides a complete set of features free of cost.



## Requirements to install Prestashop:

- Ubuntu 20.04 0r higher
- System Requirements 1GB of RAM, 2 CPU Cores, 1 GB of Disk space
- Apache2 Webserver which  is one of the most popular web servers in the world.
- AWS RDS (MYSQL) 5.0 or higher
- PHP7.4 which is a general-purpose open-source scripting language and one of the most popular programming languages for web development

## Step 1: Update system and install Apache Webserver

To begin, update the package manager cache

    sudo apt update; sudo apt install apache2 -y

![image](./assests/install-apache2.png)

## Step 2:Install PHP7.4

    sudo apt install software-properties-common; sudo add-apt-repository ppa:ondrej/php; sudo apt update; sudo apt-get install -y php7.4 php7.4-cli php7.4-zip php7.4-json php7.4-common php7.4-mysql php7.4-gd php7.4-mbstring php7.4-curl php7.4-xml php7.4-bcmath php7.4-simple php7.4-intl










