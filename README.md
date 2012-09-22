cakein
======

INTRO:
======
Bash script to clone/download, upgrade, check version of a cakephp github repo

USAGE:
======
Cakein by Maldicore Group Pvt Ltd (http://www.maldicore.com) 
Copyright 2012, Sep 23. License GNU 3.0

Usage: 		cakein OPTION [VERSION] [PROJECT]
Example: 	cakein new 2.2 mycake

OPTIONS:
	help		show this help screen
	new 		install fresh new cake installation
	up		upgrade an installation
	status		check current cakephp version
	ver 		show cakein version information

VERSION:
	cakephp versions: 1.2 1.3 2.0 2.1 2.2

PROJECT:
	project directory name

INSTALL
========
1. Give execute permission chmod +x cakein
2. Copy to /usr/bin or /usr/local/bin or in any location where it can be found

TODO
=====
Need a bit of work on the upgrade command as currently it only upgrade a github cakephp repo clone
TO Do:
- check if the project is a cakephp project based on lib/Cake folder
- check version based on lib/Cake/VERSION.txt file
- upgrade the cake project as required