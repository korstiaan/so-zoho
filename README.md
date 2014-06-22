# SO ZOHO

Shared code for the Chrome Extension and Firefox Addon which make
your ZOHO experience more pleasant.

## Description

Currently it does the following:

* Increases the height of the textarea for a bug comment. Also makes it resizable.
* Prevents accidentally closing the buginfo overlay with ESC by asking for confirmation when
  the comment textarea has content.

## Download

The prebuild packages can be downloaded from:

* Firefox: http://www.korstiaan.com/so-zoho/so-zoho.xpi
* Chrome: http://www.korstiaan.com/so-zoho/so-zoho.crx

Click [here](https://github.com/korstiaan/chrome-so-zoho#download) for instructions on how to
install the Chrome extension.

## Development

Coffeescript is used for Javascript compilation, and CSS is compiled from SASS.

Dependencies (currently only jQuery) are managed with [bower](http://bower.io/).

    $ bower install

Development for the Firefox addon takes place at: https://github.com/korstiaan/firefox-so-zoho
Development for the Chrome extension takes place at: https://github.com/korstiaan/chrome-so-zoho

## License

See LICENSE file.