How to apache 2.4 build
========================

Based on http://www.apachelounge.com/viewtopic.php?t=5032

1. Extract the zip to a folder
2. Make sure you have installed the prerequisites and the PATH variable has been set(checkbox in installer): 
  * Visual Studio VC11 
  * Windows SDK 8 
  * Python (PATH variable set) 
  * Perl (PATH variable set) 
  * Cmake (PATH variable set) 
3. Check and Modify the path configuration in build_2.4.2.bat (especially VC100_VARS_BAT). 
4. Execute build_2.4.2.bat. 
5. Wait a long time until cmake-gui spawns and follow the instructions at the gui 
6. Close cmake-gui and wait until visual studio spawns, follow the instructions in the console, save and close the solution. Press a key afterwards 
7. Wait until visual studio spawns again, and follow the instructions in the console. Press a key afterwards. 
8. Wait untill the build is done 
Often referred to as simply Apache, a public-domain open source Web server developed by a loosely-knit group of programmers. 
The first version of Apache, based on the NCSA httpd Web server, was developed in 1995.
Core development of the Apache Web server is performed by a group of about 20 volunteer programmers, called the Apache Group.
However, because the source code is freely available, anyone can adapt the server for specific needs, and there is a large public library of Apache add-ons. 
In many respects, development of Apache is similar to development of the Linuxoperating system.
The original version of Apache was written for UNIX, but there are now versions that run under OS/2, Windows and other platforms.
