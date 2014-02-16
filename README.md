# WS2-SWS-FIDDLES-SILEX

Silex Code Fiddles - A collection of Silex based projects/examples demonstrating a few parts of [Silex](http://silex.sensiolabs.org/)

## Minimum Requirements

- [Composer](http://getcomposer.org/)
- PHP 5.4

A specific project/example may have additional requirements (e.g. MySQL). See the included `README.md` that comes with each project/example.

## Installation

Each project/example has its own `README.md` containing instructions how to install and run it. Basically you'll just need to clone this repository, navigate to the specific project/example and install the dependencies using Composer before loading the project via your browser.

	$ git clone https://github.com/bramus/ws2-sws-fiddles-silex.git
	$ cd ws2-sws-fiddles-silex/<example>
	$ composer install

To install all dependencies for all examples in one go, use the one-liner below

	$ cd ws2-sws-fiddles-silex
	$ for D in `find . -mindepth 1 -maxdepth 1 -type d`; do cd $D && if [ -f composer.json ]; then composer install; fi && cd ..; done

A specific project/example may have additional installation steps (e.g. import and create the database). See the included `README.md` that comes with each project/example.