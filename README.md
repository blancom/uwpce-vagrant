# uwpce-vagrant
A vagrant build for a python development environment

![Image](screenshot.png?raw=true)

One of the challenges we face in the program is getting everyone quickly up and running with a full fledged, feature rich, functional Python development environment.  Vagrant allows us to quickly build a virtual machine with everything we'll need.

The Vagrantfile in this repo will build an Ubuntu Linux virtual machine.  It should work on Linux, OS X or Windows so that by the end of the installation you will have an Ubuntu Linux virtual machine running on top of your host operating system, be it OS X, Windows, or another instance of Linux.

Prerequisites
-------------

1.  Install Virtual Box for your host operating system

    https://www.virtualbox.org

2.  Install Vagrant for your host operating system

    https://www.vagrantup.com

Installation Steps
------------------

1.  Attach your computer to a fast network, attach your laptop to a power supply to prevent it from going to sleep, provide for up to four hours for the 'vagrant up' command to do its work.  When wired into a descent home network 'vagrant up' might take only twenty minutes.

2.  Clone this repo, change into the directory and start the vagrant build:

    ```
    $ git clone https://github.com/UWPCE-PythonCert/uwpce-vagrant.git
    $ cd uwpce-vagrant
    $ vagrant up
    ```

3.  Restart your new virtual computer and login:

    ```
    $ vagrant reload
    ```

    Username: vagrant<br>
    Password: vagrant

Usability Notes
---------------

Disable screen saver and power management within the virtual machine.  These issues are best left to the host computer.

![Image](screenshot-screensaver.png?raw=true)
