Backend-PHP
============

Backend-PHP is a basic code base that provides REST functionality using MVC architecture.
It's ideal for developing API's that should provide information in multiple formats, or
an API that also needs to act as a web site.

It also has the following advantages:

* Unit Testable and Tested using PHPUnit
* PSR0, PSR1 and PSR2 compliant
* Results can be modified on a per format basis

It serves as the ideal low level base for applications or frameworks that need to be
RESTful and done using MVC. 

Installation
----------

    git clone git@github.com:backend/core-system.git
    composer install

`composer` will install all the necessary dependencies. If you're not familiar with
composer, check out http://getcomposer.org.

Core
----

The Backend-Core tier provides only basic Request / Response functionality, coupled
with dependency injection and event management, to provide a simple base to build
applications from. It's ideal for building single purpose API's where the callbacks
will handle logic and formatting.

Next Step
---------

For more information, read the documentation on http://backend-php.net
