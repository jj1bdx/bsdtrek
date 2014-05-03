bsdtrek
========

This Star Trak game is originally from FreeBSD, with minimal change to build on Linux with pmake too.

## Travis CI build status for the master branch

[![Build Status](https://travis-ci.org/jj1bdx/bsdtrek.svg?branch=master)](https://travis-ci.org/jj1bdx/bsdtrek)

## FreeBSD `trek` source code

* Based on the ports [SVN revision r328087](http://svnweb.freebsd.org/ports/head/games/bsdgames/Makefile?revision=328087&view=markup) (tagged bsdtrek\_dragonflybsd)
* See also <http://gitweb.dragonflybsd.org/dragonfly.git/tree/v2.4.0:/games>

## On OS X

* Use `bsdmake` from MacPorts or Homebrew
    * setrlimit error message patch required <https://trac.macports.org/ticket/35612>

## On Ubuntu (and Travis CI)

* Require `sudo apt-get install pmake` and use `pmake` instead of `make`
