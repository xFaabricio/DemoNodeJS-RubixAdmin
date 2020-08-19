# DemoNodeJS-RubixAdmin

# For Windows users only:

If you are on Windows, you need to setup your system to be able to compile Node native modules. There are two options available:

- Option 1 (recommended): Install all the required tools and configurations using Microsoft's windows-build-tools for compiling Node modules.

	To do that just run: 

		npm install --global --production windows-build-tools 
	
	From an elevated PowerShell or CMD.exe (run as Administrator).
	
- Option 2: Install tools and configuration manually:

        Visual C++ Build Environment:
	
         Option 1: Install Visual C++ Build Tools using the Default Install option.
	 
         Option 2: Install Visual Studio 2015 (or modify an existing installation) and select Common Tools for Visual C++ during setup. This also works with the free Community and Express for Desktop editions.
	 
	💡[Windows Vista / 7 only] requires .NET Framework 4.5.1
	
Install Python 2.7 (v3.x.x is not supported), and run npm config set python python2.7

Launch cmd, npm config set msvs_version 2015

# Setup the Node Seed Project

- Then install all NPM dependencies:

		npm install

- Once installed, launch the web server like so:

		npm start
