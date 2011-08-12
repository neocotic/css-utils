# [CSS Utils](http://forchoon.com/projects/css3/css-utils/)

A utility for providing common CSS3 classes in a single file.

I found myself rewriting so many standard classes for every website I created
and so I decided to group all of these general classes in to a single file.

The classes provided are simple in design and function with the idea that you
use multiple classes on your HTML elements as opposed to creating more complex
classes for single elements. Obviously this approach isn't always the best but
it gives you that option and comes in exceptionally handy for blogs.

## Classes

Since there are potentially over 800 classes provided I highly recommend that
you take a look at the file you want to use for an idea of what classes are
available.

That said; the naming conventions I've used for the selectors are pretty
standard and simple to avoid confusion. Some of the longer names also have
shorter versions available to make the HTML a bit cleaner and more
understandable without the need for an inspector tool.

## File Choice

There are two choices as to what file you want to use based on whether or not
you want to have colour-specific classes available.

* `utils.css` - Standard classes
* `utils.colors.css` - Standard & colour-specific classes

I created this choice because over 500 additional classes exist for the colours
alone as all SVG colours are included and not all users may need them so a
lighter option is available.

## Possible Conflicts

Since you're adding so many new classes there is a clear possibility of
conflicting class names so you should always test your pages after adding CSS
Utils as your implementation of a class may differ from this.

CSS Utils doesn't add the `!important` rule to any of the styles applied in an
attempt to minimize unwanted conflicts.