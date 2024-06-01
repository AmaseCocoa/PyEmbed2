# PyEmbed2

![PyPI - Python Version](https://img.shields.io/pypi/pyversions/pyembed2) ![PyPI - Downloads](https://img.shields.io/pypi/dw/pyembed2)

[OEmbed](http://oembed.com) consumer library for Python with automatic
discovery of producers.

PyEmbed2 is A version of PyEmbed with some fixes and added features. It was forked primarily for use in my project, but should work fine.

PyEmbed2 allows you to easily embed content on your website from a wide
variety of producers (including [Flickr](http://flickr.com),
[Twitter](http://twitter.com) and [YouTube](http://youtube.com)). Unlike
many OEmbed consumers, you don\'t need to configure each producer that
you want to use - PyEmbed2 discovers the configuration automatically.

You just need to provide the URL, and PyEmbed2 will generate a block of
HTML, ready for you to include in your page:

    >>> from pyembed.core import PyEmbed
    >>> html = PyEmbed().embed('http://www.youtube.com/watch?v=9bZkp7q19f0')
    <iframe width="480" height="270" src="http://www.youtube.com/embed/9bZkp7q19f0?feature=oembed" frameborder="0" allowfullscreen></iframe>

There are plugins for embedding content into
[Markdown](https://pypi.python.org/pypi/pyembed-markdown) and
[reStructuredText](https://pypi.python.org/pypi/pyembed-rst) documents,
and for customizing embeddings with
[Jinja2](https://pypi.python.org/pypi/pyembed-jinja2) and
[Mustache](https://pypi.python.org/pypi/pyembed-mustache) templates. For
more information, see the [PyEmbed2](http://pyembed.github.io) website.

## Changes from PyEmbed
* Support for Python 2.x and Python 3.8 and below has been discontinued.
* Include jaywink/pyembed changes

## Compatibility

PyEmbed2 has been tested with Python 3.8 onwards.

## Installation

PyEmbed2 can be installed using pip:

    pip install pyembed2

When installing the latest development version (requires git): 

    pip install git+https://github.com/AmaseCocoa/PyEmbed2.git
## Contributing

To report an issue, request an enhancement, or contribute a patch, go to
the PyEmbed2 [GitHub](hhttps://github.com/AmaseCocoa/PyEmbed2) page.

## License

PyEmbed2 is distributed under the MIT license.


    Copyright (c) 2024 AmaseCocoa

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.


    Copyright (c) 2013 Matt Thomson

    Permission is hereby granted, free of charge, to any person obtaining
    a copy of this software and associated documentation files (the
    "Software"), to deal in the Software without restriction, including
    without limitation the rights to use, copy, modify, merge, publish,
    distribute, sublicense, and/or sell copies of the Software, and to
    permit persons to whom the Software is furnished to do so, subject to
    the following conditions:

    The above copyright notice and this permission notice shall be
    included in all copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
    EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
    MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
    NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
    LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
    OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
    WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
