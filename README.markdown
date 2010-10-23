PHP Hudson tools
================

Overview
--------

The PHP Hudson toolset is primarily intended to provide a basis for
the continuous integration of [Horde](http://www.horde.org). It helps
to enforce commercial grade quality guidelines for the Horde code base
and allows to publish this to the outside.

As the name implies the toolset is primarily oriented towards
providing the standard PHP QA toolset for the [Continuous Integration
server Hudson](http://www.hudson-ci.org).

The content of the package is a collection of
[PEAR](http://pear.php.net) based packages and an ant script for
automated installation. Thus you can basically use the resulting
toolset for any other purpose in the field of PHP QA, too.

The included software in detail:

 - [PHPUnit](http://phpunit.de)
 - [PHP Depend](http://pdepend.org)
 - [PHP Documentor](http://www.phpdoc.org)
 - [PEAR CodeSniffer](http://pear.php.net/PHP_CodeSniffer)
 - [PHP Mess Detector](http://phpmd.org)
 - [PHP Copy Paste Detector](http://github.com/sebastianbergmann/phpcpd)
 - [PHP Code Browser](http://github.com/mayflowergmbh/PHP_CodeBrowser)
 - [Horde Components](http://wiki.horde.org/Doc/Dev/Component/Components)

The toolset hopefully helps to get you up and running with PHP QA in
no time.

Requirements
------------

In order to use the toolset three dependencies are required:

 - PHP5
 - PEAR
 - Ant

Installation
------------

If you want to install all tools beside the Components package (which
is rather specific to Horde) you can run:

    ant

In order to install everything you can run:

    ant horde
