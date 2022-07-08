# gazebo simulation for spotmicro


## Installing ignition gazebo-fortress on the uBuntu focal(20.04.04)

$ sudo apt-get update
$ sudo apt-get install lsb-release wget gnupg

$ sudo wget https://packages.osrfoundation.org/gazebo.gpg -O /usr/share/keyrings/pkgs-osrf-archive-keyring.gpg
$ echo "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/pkgs-osrf-archive-keyring.gpg] http://packages.osrfoundation.org/gazebo/ubuntu-stable $(lsb_release -cs) main" | $ $ 

$ sudo tee /etc/apt/sources.list.d/gazebo-stable.list > /dev/null
$ sudo apt-get update
$ sudo apt-get install ignition-fortress

 ## run simulation
$ ign gazebo empty.sdf

