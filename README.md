Logitech K810 Function Key Switcher for Mac OS X
================================================

About
=====

This app Mac version of https://github.com/chres/bin/tree/master/k810 with Linux's hidraw
replaced by [signal11/hidapi](https://github.com/signal11/hidapi) library.

It requires root privileges to run, so in order to be run it has to have
setuid bit set before launching.

Feel free to work with it and use as needed.

Original reverse engineering was done by [Mario Scholz](http://www.trial-n-error.de/posts/2012/12/31/logitech-k810-keyboard-configurator/).

Download for OS X 10.10
=======================

https://github.com/niieani/k810_fkeys_mac/releases

How to run
==========

Run from terminal as root (on every boot):

```sudo ./k810-fn-fix on```

To turn the fix off:

```sudo ./k810-fn-fix off```

The OS X port was made by Przemysław Kamiński.
This build was compiled by Bazyli Brzóska.

Compilation with XCode
======================

 * Clone the repository
 * Install XCode
 * Start terminal in the directory of the repository

```
cd ./xcode
xcodebuild -configuration Release
```
