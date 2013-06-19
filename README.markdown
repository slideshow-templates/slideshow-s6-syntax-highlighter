# S6 Syntax - Slide Show (S9) Template Pack

## What's Slide Show (S9)?

A Ruby gem that lets you create slide shows and author slides in plain text
using a wiki-style markup language that's easy-to-write and easy-to-read.
More [Slide Show (S9) Project Site »](http://slideshow-s9.github.io)

## Intro

The [S6 Blank](http://github.com/geraldb/s6) package bundled up into 
a Slide Show (S9) template pack. Includes [SyntaxHighlighter](http://alexgorbatchev.com/SyntaxHighlighter) - a free, open source
syntax highlighter in JavaScript.
 
## Try It Yourself - How To Use the Template Pack

If you want to try it yourself, install (fetch) the new template pack. Issue the command:

    $ slideshow install s6syntax

Or as an alternative clone the template pack using `git`. Issue the commands:

    $ cd ~/.slideshow/templates
    $ git clone git://github.com/slideshow-s9/slideshow-s6-syntax-highlighter.git

To check if the new template got installed, use the `list` command:

    $ slideshow list

Listing something like:

    Installed templates include:
       s6syntax.txt (~/.slideshow/templates/s6syntax/s6syntax.txt)

Now you're ready to use it using the `-t/--template` switch. Example:

    $ slideshow build tutorial -t s6syntax.txt

That's it.


## Questions? Comments?

Questions? Comments?
Send them along to the [Free Web Slide Show Alternatives (S5, S6, S9, Slidy And Friends) Forum/Mailing List](http://groups.google.com/group/webslideshow).
Thanks!
