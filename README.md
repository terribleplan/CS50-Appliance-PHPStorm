CS50-Appliance-PHPStorm
=======================

Installing PhpStorm
-------------------

Installing PHPStorm on the CS50 appliance is relatively easy because it comes with Java, albeit the OpenJDK-JRE, preinstalled.

The OpenJDK may cause some visual issues with the OpenJDK, but they are easily solved just by relaunching the application. The alternative is replacing the OpenJDK with Oracle's proprietary version, and is far more difficult than the small benefit gained.

1. Go [here](http://www.jetbrains.com/phpstorm/download/download_thanks.jsp?os=linux) and the download will start automatically
1. Open up a terminal and run this command:
```
tar xf Downloads/PhpStorm-*.tar.gz
```
1. Now you need to relocate the program to a more sane place
```
mv PhpStorm* PhpStorm
```
1. Finally you should run the program for the first time (from the command line still)
```
PhpStorm/bin/phpstorm.sh
```
1. Choose to evaluate the application, and accept the license agreement
1. Check the box that says "Create desktop shortcut" as well as the one that says "For all users"
1. Close the window

Phpstorm is now installed and accessible from the menu! You have 30 days to mess around with it before you will need to acquire a license.

Getting PhpStorm to be Useful
-----------------------------
//TODO

License
=======
This document is made available under a [CC BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/) license, the  full text of which can be found [online](http://creativecommons.org/licenses/by-sa/4.0/legalcode) or in the [LICENSE](LICENSE) file.

Contributing
============
If you have any additional ideas you wish to share, or any additions/corrections to this document, please open a pull request. Please do not add yourself to the "Authors" section, this will be done by the repository owner. Note that terms of the [contribution guidelines](CONTRIBUTING.md) apply.