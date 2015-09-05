PhpStorm-Resources
==================

PhpStorm is making inroads at Automattic. Here you'll find various helpful files we've made.


WordPress Support in PhpStorm
---------
PhpStorm has added support for WordPress as of Version 8. There is an [in depth tutorial](http://confluence.jetbrains.com/display/PhpStorm/WordPress+Development+using+PhpStorm) to learn how to use these new features for WordPress development (including plugins, themes and core).


WordPress.xml
-------------
While PhpStorm now has native support (see above), sometimes you still want to enforce it's code style on other projects. `WordPress.xml` is the PhpStorm code style configuration file that you can use to do this. It tells PhpStorm to as closely match WordPress's recommended formatting style as possible.

To install it, find your [configuration directory](http://www.jetbrains.com/phpstorm/webhelp/project-and-ide-settings.html) and then put it in the `/config/codestyles/` subfolder.