[![WebSight Designs](http://www.websightdesigns.com/img/headerlogo-light.png)](http://www.websightdesigns.com)

sublime-text-snippets
=====================

Sublime Text snippets allow you to create your own shortcuts to writing out snippets of code you reuse frequently. Sublime Text snippets are generally compatible with Textmate snippets. Sublime Text snippet files are XML files with the `.sublime-snippet` file extension.

Full documentation on writing snippets is available from:

http://docs.sublimetext.info/en/latest/extensibility/snippets.html

## Mac OS X

    $ cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/User/

## Windows 7 (with Cygwin / Git Bash)

	$ cd "%AppData%\Sublime Text 3\Packages\User"

## Download Instructions

	$ git clone https://github.com/websightdesigns/sublime-text-snippets.git

## Install Instructions

    $ mv sublime-text-snippets/*.sublime-snippet .

## Uninstall Instructions

    $ mv ./*.sublime-snippet sublime-text-snippets/

## Snippet Categories

* PHP
* JavaScript
* jQuery
* CSS
* HTML
* Global Scope

## Developer Notes

To determine the correct scope key to use, press `CMD+ALT+P` (on Mac OS X) in a file of the desired scope and it will show up in the status bar.
