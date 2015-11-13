Windows binaries for freezer
========================

Freezer is a Backup Restore DR as a Service platform that helps you to automate the data backup and
restore process. [freezer on openstack](https://github.com/openstack/freezer)

In order to work on windows, freezer needs tar binaries, the goal of this repo is to provide those binaries and their source code outside outside the main repo.


Binaries included
-----------------------

 - bunzip2.exe
 - bzcat.exe
 - bzip2.exe
 - bzip2recover.exe
 - cygbz2-1.dll
 - cygiconv-2.dll
 - cygintl-8.dll
 - cygwin1.dll
 - find.exe
 - gzip.exe
 - tar.exe
 - trickle
 - trickle-overload.so
 - xz.exe

How to deploy
------------------

just clone this repo inside freezer path, e.g.

    git clone https://github.com/memogarcia/freezer-windows-binaries C:\\Python27\\Lib\\site-packages\\freezer

and that's it

LIcense
---------
All binaries include their own source code and license file.
