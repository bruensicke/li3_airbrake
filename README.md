# li3_airbrake

lithium library that reports php errors back to airbrake.io webservice

## Installation

Add a submodule to your li3 libraries:

	git submodule add git@github.com:bruensicke/li3_airbrake.git libraries/li3_airbrake

and activate it in you app (config/bootstrap/libraries.php), of course:

	Libraries::add('li3_airbrake');

## Usage

Just throw Exception like there is no morning. Do not forget to insert meaningful messages.
Do not forget to create useful and well namedd Exception classes on your own, like this:

	class AppException extends Exception {

	}

## Credits

* [li3](http://www.lithify.me)
* [Nodrew](https://github.com/nodrew/php-airbrake/)

