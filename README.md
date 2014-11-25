Laravel-Master
==============

Laravel is a web application framework with expressive, elegant syntax.
We believe development must be an enjoyable, creative experience to be 
truly fulfilling. Laravel attempts to take the pain out of development 
by easing common tasks used in the majority of web projects, such as authentication, 
routing, sessions, and caching. Laravel aims to make the development 
process a pleasing one for the developer without sacrificing application 
functionality. Happy developers make the best code. To this end, 

we've attempted to combine the very best of what we have seen in other 
web frameworks, including frameworks implemented in other languages, 
such as Ruby on Rails, ASP.NET MVC, and Sinatra. Laravel is accessible, 
yet powerful, providing powerful tools needed for large, robust applications. 
A superb inversion of control container, expressive migration system, 
and tightly integrated unit testing support give you the tools you need 
to build any application with which you are tasked.

Installation
==============

download OR Pull these files and run on your server
http://your-server-domain/laravel

laravel is the project directory



Install Laravel
------------------------------------------------------------------------
Via Laravel Installer

First, download the Laravel installer using Composer.
composer global require "laravel/installer=~1.1"

Make sure to place the ~/.composer/vendor/bin directory in your PATH so 
the laravel executable is found when you run the laravel command in your
erminal.

Once installed, the simple laravel new command will create a fresh Laravel
installation in the directory you specify. For instance, laravel new blog 
would create a directory named blog containing a fresh Laravel installation 
with all dependencies installed. This method of installation is much faster 
than installing via Composer.


Via Composer Create-Project
You may also install Laravel by issuing the Composer create-project 
command in your terminal:
composer create-project laravel/laravel --prefer-dist

Server Requirements
========================================================================
The Laravel framework has a few system requirements:

    PHP >= 5.4
    MCrypt PHP Extension

As of PHP 5.5, some OS distributions may require you to manually install
the PHP JSON extension. When using Ubuntu, this can be done via apt-get 
install php5-json.
