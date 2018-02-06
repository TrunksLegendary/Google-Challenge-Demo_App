# Grow with Google Challenge 
## Setup Development Enviornment on CenotOS 7



VMWare Workstation Pro or Virtual Box
CentOS DVD
Host workstation

I have a windows 10 workstaion

---
## Install Node.js
>sudo yum install curl sudo

>sudo yum install epel-release

>sudo curl --silent --location https://rpm.nodesource.com/setup_9.x | sudo bash -

>sudo sudo yum install nodejs

---
## Check Node.js version
>node --v


## Setup Git repo and Pull from 
>mkdir git/googleDev
>cd git/googleDev
>git init

>git pull https://github.com/jakearchibald/wittr

>git pull https://github.com/TrunksLegendary/Google-Challenge-Demo_App---->

---
## install NPM

Change directory to the cloned repo


>npm install

## Start the server
>npm run serve