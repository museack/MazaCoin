##Mazacoin /(OSX Mavericks Fork)

http://www.MazaCoin.org


Copyright (c) 2009-2013 Bitcoin Developers

Copyright (c) 2013 Zetacoin Developers

Copyright (c) 2014 Mazacoin Developers

##What is MazaCoin?
````
MazaCoin is an experimental new digital currency that enables instant payments to
anyone, anywhere in the world. MazaCoin uses peer-to-peer technology to operate
with no central authority: managing transactions and issuing money are carried
out collectively by the network. MazaCoin is also the name of the open source
software which enables the use of this currency.

For more information, as well as an immediately useable, binary version of
the MazaCoin client sofware, see www.MazaCoin.org
````

##*NIX Build Instructions
Tested build on Ubuntu 12.X
Required packages:
````
ntp git build-essential libssl-dev libdb-dev libdb++-dev 
libboost-all-dev libqrencode-dev libcurl4-openssl-dev automake make
````
Debian 6:
````
ntp git build-essential libssl-dev libdb-dev libboost-all-dev 
libqrencode-dev libcurl4-openssl-dev automake make libdb4.8++-dev 4.8.30-2

````

##Build Info
````
git clone https://github.com/MazaCoin/MazaCoin.git
cd MazaCoin/src
make -f makefile.unix USE_UPNP=-

Output: mazacoind
````
For smaller RAM systems, you may need to create a swap file for systems to build. 
This usually happens with under 1GB RAM
UBUNTU:
````
sudo dd if=/dev/zero of=/swapfile bs=64M count=16
sudo mkswap /swapfile
sudo swapon /swapfile
````




##Note
````
This is a fork of ZetaCoin that works on OSX Mavericks with brew. Use at your own risk.
````
##License
````
MazaCoin is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.
````
