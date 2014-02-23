# angular-haml-sass-coffeescript-bootstrap

This is a haml-ifed, sass-ified and caffeinated version of the original
[angular-seed](https://github.com/angular/angular-seed). It provides the same stub application plus
an automatic background compilation process for [CoffeeScript](http://coffeescript.org/),
[SASS](http://sass-lang.com/) and [HAML](http://haml.info/). All JS, CSS and HTML files of the
original project have been ported to serve as an example.

Directories:

  src - Keep all your source files here
  app - Compiled or copied version of the source, better not touch.

## Install

```git clone```
```bundle install```

## Background compiler

Start the background-compiler with ```./compiler```. It will start compiling once you touch a file.
All files which do not need to be compiled will only be copied. If you delete a file from ```src```
it's counter-part will also be removed.

## Webserver

I added a quick webserver script which points to ```app```. Start with ```./server```.
Move your browser to ```http://localhost:4000```

