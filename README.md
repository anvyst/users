CakeDC Users Plugin
===================

[![Bake Status](https://secure.travis-ci.org/CakeDC/users.png?branch=3.x)](http://travis-ci.org/CakeDC/users)
[![Downloads](https://poser.pugx.org/CakeDC/users/d/total.png)](https://packagist.org/packages/CakeDC/users)
[![Latest Version](https://poser.pugx.org/CakeDC/users/v/stable.png)](https://packagist.org/packages/CakeDC/users)

IMPORTANT: 3.x version is ALPHA status now, we are improving and testing it now.

The **Users** plugin is back! 

It covers the following features:
* User registration 
* Login/logout
* Social login (Facebook, Twitter)
* Simple RBAC
* Remember me (Cookie)
* Manage user's profile
* Admin management

The plugin is here to provide users related features following 2 approaches:
* Quick drop-in working solution for users login/registration. Get users working in 5 minutes.
* Extensible solution for a bigger/custom application. You'll be able to extend:
  * UsersAuth Component
  * Use your own UsersTable
  * Use your own Controller

On the previous versions of the plugin, extensibility was an issue, and one of the main 
objectives of the 3.0 rewrite is to guarantee all the pieces could be extended/reused as
easily.

Another decision made was limiting the plugin dependencies on other packages as much as possible.

Requirements
------------

* CakePHP 3.0+
* PHP 5.4.16+

Documentation
-------------

For documentation, as well as tutorials, see the [Docs](Docs/Home.md) directory of this repository.

Roadmap
------

* 3.0.0 Migration to CakePHP 3.x
* 3.0.1 General improvements
  * Unit test coverage improvements
  * Refactor UsersTable to Behavior
  * Add google authentication
  * Add captcha
  * Link social accounts in profile

Support
-------

For bugs and feature requests, please use the [issues](https://github.com/CakeDC/users/issues) section of this repository.

Commercial support is also available, [contact us](http://cakedc.com/contact) for more information.

Contributing
------------

This repository follows the [CakeDC Plugin Standard](http://cakedc.com/plugin-standard). If you'd like to contribute new features, enhancements or bug fixes to the plugin, please read our [Contribution Guidelines](http://cakedc.com/contribution-guidelines) for detailed instructions.

License
-------

Copyright 2015 Cake Development Corporation (CakeDC). All rights reserved.

Licensed under the [MIT](http://www.opensource.org/licenses/mit-license.php) License. Redistributions of the source code included in this repository must retain the copyright notice found in each file.