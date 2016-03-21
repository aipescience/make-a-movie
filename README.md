make-a-movie
============

This script takes all eps files from DIRECTORY, and

* converts them to png,
* montages them on a black background,
* and finally converts the png files into a movie

(c) Jochen Klar, July 2011, AIP e-Science

Acknowlegments to Arman Khatalayan and Kristin Riebe on whose skripts this application is based on.

Prereqesites
------------

* python 2.x
* imagemagick
* mencoder

Examples
--------

Create a movie for Linux with a square window:

```
make-a-movie <dir> -g 1024x1024
```

Create a movie for Linux with a lower framerate:

```
make-a-movie <dir> -f 15
```

Create a movie for Windows in DVD resolution:

```
make-a-movie <dir> --preset=win
```

Create a movie for Mac in HD resolution:

```
make-a-movie <dir> --preset=mac-hd
```

References
----------

* http://personal.cscs.ch/~mvalle/mencoder/mencoder.html
* http://www.mplayerhq.hu/DOCS/HTML/en/menc-feat-quicktime-7.html
* http://lists.mplayerhq.hu/pipermail/mencoder-users/2007-October/007194.html
