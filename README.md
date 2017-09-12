                                               888    d8b 888
                                               888    Y8P 888
                                               888        888
     .d8888b .d8888b  .d8888b         888  888 888888 888 888 .d8888b
    d88P"    88K      88K             888  888 888    888 888 88K
    888      "Y8888b. "Y8888b. 888888 888  888 888    888 888 "Y8888b.
    Y88b.         X88      X88        Y88b 888 Y88b.  888 888      X88
     "Y8888P  88888P'  88888P'         "Y88888  "Y888 888 888  88888P'

[css-utils](https://github.com/neocotic/css-utils) is a utility for providing common CSS3 classes in a single file.

I found myself rewriting so many standard classes for every website I created and so I decided to group all of these
general classes in to a single file.

The classes provided are simple in design and function with the idea that you use multiple classes on your HTML elements
as opposed to creating more complex classes for single elements. Obviously this approach isn't always the best but it
gives you that option and comes in exceptionally handy for blogs.

[![License](https://img.shields.io/github/license/neocotic/css-utils.svg?style=flat-square)](https://github.com/neocotic/css-utils/blob/master/LICENSE.md)
[![Release](https://img.shields.io/github/release/neocotic/css-utils.svg?style=flat-square)](https://github.com/neocotic/css-utils/releases)

* [Install](#install)
* [Classes](#classes)
* [Possible Conflicts](#possible-conflicts)
* [Bugs](#bugs)
* [Contributors](#contributors)
* [License](#license)

## Install

There are two choices as to what file you want to use based on whether or not you want to have colour-specific classes
available.

* [utils.css](https://cdn.rawgit.com/neocotic/css-utils/master/utils.css) (11kb) – Standard classes
* [utils.colors.css](https://cdn.rawgit.com/neocotic/css-utils/master/utils.colors.css) (39kb) – Standard & colour-specific classes

I created this choice because over 500 additional classes exist for the colours alone as all SVG colours are included and
not all users may need them so a lighter option is available.

## Classes

Since there are potentially over 800 classes provided I highly recommend that you take a look at the file you want to
use for an idea of what classes are available.

That said; the naming conventions I've used for the selectors are pretty standard and simple to avoid confusion. Some of
the longer names also have shorter versions available to make the HTML a bit cleaner and more understandable without the
need for an inspector tool.

## Possible Conflicts

Given how many new classes you're adding there is a clear possibility of conflicting class names so you should always
test your pages after adding [css-utils](https://github.com/neocotic/css-utils) as your implementation of a class may
differ from this.

[css-utils](https://github.com/neocotic/css-utils) doesn't add the `!important` rule to any of the styles applied in an
attempt to minimize unwanted conflicts.

## Bugs

If you have any problems with css-utils or would like to see changes currently in development you can do so
[here](https://github.com/neocotic/css-utils/issues).

## Contributors

If you want to contribute, you're a legend! Information on how you can do so can be found in
[CONTRIBUTING.md](https://github.com/neocotic/css-utils/blob/master/CONTRIBUTING.md). We want your suggestions and pull
requests!

A list of css-utils contributors can be found in
[AUTHORS.md](https://github.com/neocotic/css-utils/blob/master/AUTHORS.md).

## License

Copyright © 2017 Alasdair Mercer

See [LICENSE.md](https://github.com/neocotic/css-utils/blob/master/LICENSE.md) for more information on our MIT license.
