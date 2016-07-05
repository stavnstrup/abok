# naf4-publication
Development of an architectural book of knowledge based on NAF4



## Running Jekyll on our own machine

If you want to setup a development environment, you need to install [Virtual
Box](https://www.virtualbox.org/) and [Vagrant](https://www.vagrantup.com/) on
you local machine.

To create the virtual machine, you need to follow the following steps.

1. Create the virtual machine

       $ vagrant up

   Note the above instructions is supposed to provision the box as well, However, due to changes in latest Ubuntu 16.04, Vagrant version 1.8.1 or older fails to provision during creation.

   It might therefore be necessary to provision the machine in a separate step by running the command

       $ vagrant provision

2. Open a shell. Goto the directory where the repository is located and run the command

       $ vagrant ssh

3. Now you are logged in to the virtual machine and can run the following commands, which will force Jekyll to generate new files, whenever the sources have changed

       $ cd /vagrant
       $ jekyll serve --host 0.0.0.0 --force_polling

From time to time, Jekyll might stop automatically generate files. If that is the case, then just restart Jekyll.
