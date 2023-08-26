# miniProxy

Originally written *by Joshua Dick* *([src](http://joshdick.github.io/miniProxy))*.    
Modified with PHP8 support by @aaviator42.

Last edit: `2023-08-25`.


---

## About miniProxy

miniProxy is a simple web proxy written in PHP that can allow you to bypass Internet content filters, or to browse the internet anonymously. miniProxy is licensed under the [GNU GPL v3](https://www.gnu.org/licenses/gpl-3.0.html). 

## Prerequisites

This version of miniProxy should be able to run on any web server with PHP 8.0 or later. miniProxy requires PHP's `curl` and `mbstring` extensions to be installed.

## Installation and Use

Simply copy `miniProxy.php` to your web server (it's okay to rename it) and access it directly. That's it! You'll be presented with further usage instructions.

miniProxy doesn't require any configuration out of the box, but configuration options are available; see the top of `miniProxy.php` for details.

## Known Limitations

miniProxy has several known limitations. Some of them may be fixed in future releases. For now, they include:

* `<object>` tags are not handled
* No cookie support
* Basic AJAX support, but only for browsers that use `XMLHttpRequest`

## Contact and Feedback

If you'd like to contribute to miniProxy or file a bug or feature request, please visit [its GitHub page](https://github.com/aaviator42/miniProxy).

