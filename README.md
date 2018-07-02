# API Server Wrapper

****************BASH SCRIPT FOR GAME API SERVER HOSTING********************

This is a Bourne Again SHell (BASH) script is for the initial setup of a server
that is meant to host a CRUD API for player stats and world data.  

The intended use case of this server is:

1. Add MMO elements to a game that is played mostly locally
2. Store data that will be updated once every 10 minutes.
3. HTTP based API hosting


It will deploy a 64 bit Ubuntu 14.04 server with:

PHP 7.2

nginx

MySQL 5.7

Composer







There is also a Vagrant server setup file.  Tested using VirtualBox and Vagrant.

-------------------------------------------------------------------------------------------

VAGRANT INSTRUCTIONS:

First install Vagrant and VirtualBox

1. Copy this repository
2. Open command prompt and change to the directory of the repository (use CD command) 
3. Type: vagrant up 


