# angular-haml-sass-coffeescript-seed

This is a haml-ifed, sass-ified and caffeinated version of the original
[angular-seed](https://github.com/angular/angular-seed). It provides the same stub application plus
an automatic background compilation process for [CoffeeScript](http://coffeescript.org/),
[SASS](http://sass-lang.com/) and [HAML](http://haml.info/). All JS, CSS and HTML files of the
original project have been ported to serve as an example.

Directories:

    src - Keep all your source files here, contains ported angular-seed app data
    app - Compiled or copied version
    ... all others are just copies from angular-seed

There are a lot of little seeders with all extensions out there but I built this one because it
produces a clean deployable ```app```-directory without any _pre or the likes. Also it uses Ruby
over node.js for compiling and web-serving.

## Install

- ```git clone https://github.com/chrp/angular-haml-sass-coffeescript-seed.git```
- ```bundle install``` (Which will require you to have [Bundler](http://bundler.io/) installed)

## Background compiler

Start the background-compiler with ```./compiler```. It will start compiling once you touch a file.
All files which do not need to be compiled will only be copied. If you delete a file from ```src```
it's counter-part from ```app``` will also be removed.

## Webserver

I added a quick webserver script with ```app``` as it's document root.

- Start with ```./server```.
- Move your browser to ```http://localhost:4000```

