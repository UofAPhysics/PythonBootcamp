## Python in Physics Bootcamp

### Getting started

We will need to download and install a python distribution.  Every user has their own python distribution, which allows you to use whatever packages in python are necessary for your work.  Our industry-standard approach is to download the Anaconda python distribution, which bundles all the really important parts of the python universe into one place.  The package can be downloaded from [here](https://www.anaconda.com/download/).   If you right-click on the link and copy the link in your web-browser, you can usually paste the file into the command line.  We'll want to download the file using the command `wget` ("web get", I guess).  When I wrote this, you can also get the links [here](https://repo.anaconda.com/archive/).  You can then run the installer with the `source` command.
You can then run the installer with the `source` command.

	wget https://repo.anaconda.com/archive/Anaconda3-5.2.0-Linux-x86_64.sh
	bash Anaconda3-5.2.0-Linux-x86_64.sh

or on a terminal on a Mac

	curl -O https://repo.anaconda.com/archive/Anaconda3-5.2.0-MacOSX-x86_64.pkg
	open Anaconda3-5.2.0-MacOSX-x86_64.pkg
	
Make sure you change the location of the python install to be a place where you have ample room.  At the end of the installation process, the script may ask if you want to append the startup commands to your `.bashrc` file.  You will want to say "yes" so that the version of python you use is the one that you just installed.  
