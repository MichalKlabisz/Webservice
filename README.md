# Webservice

[![Build Status](https://img.shields.io/travis/UseMuffin/Webservice/master.svg?style=flat-square)](https://travis-ci.org/UseMuffin/Webservice)
[![Coverage](https://img.shields.io/coveralls/UseMuffin/Webservice/master.svg?style=flat-square)](https://coveralls.io/r/UseMuffin/Webservice)
[![Total Downloads](https://img.shields.io/packagist/dt/muffin/webservice.svg?style=flat-square)](https://packagist.org/packages/muffin/webservice)
[![License](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](LICENSE)

Extremely simplistic webservices for CakePHP 3.

## Install

Using [Composer][composer]:

```
composer require muffin/webservice:dev-master
```

You then need to load the plugin. You can use the shell command:

```
bin/cake plugin load Muffin/Webservice
```

or by manually adding statement shown below to `boostrap.php`:

```php
Plugin::load('Muffin/Webservice');
```

## Usage

You can only use this plugin as a base to a separate plugin or to manage custom webservice
drivers connections.

_Examples coming soon..._

## Patches & Features

* Fork
* Mod, fix
* Test - this is important, so it's not unintentionally broken
* Commit - do not mess with license, todo, version, etc. (if you do change any, bump them into commits of
their own that I can ignore when I pull)
* Pull request - bonus point for topic branches

To ensure your PRs are considered for upstream, you MUST follow the CakePHP coding standards.

## Bugs & Feedback

http://github.com/usemuffin/webservice/issues

## License

Copyright (c) 2015, [Use Muffin] and licensed under [The MIT License][mit].

[cakephp]:http://cakephp.org
[composer]:http://getcomposer.org
[mit]:http://www.opensource.org/licenses/mit-license.php
[muffin]:http://usemuffin.com
