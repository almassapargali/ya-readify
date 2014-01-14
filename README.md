# Yet Another Readify

This is Octopress theme based on awesome [Readify](https://github.com/vladigleba/readify) theme. Layouts taken from original Classic theme, and styles from Readify, though I made some changes.

# Changes

- Removed multi-author support, it doesn't show post author after blog posts.
- Removed default index, which shows excerpts of latest posts. Instead using archive as index.
- Removed year delimiters from archive list.
- Removed support for categories.
- Removed sidebar support.
- Changed styles a bit.
- Adding custom urls in navigation option. Using:

	```
# add this in _config.yml
navigation_urls: [{title: 'About me', url: 'http://almassapargali.com'}]
```

Live demo at [my blog](http://blog.almassapargali.com).

# Install

    cd octopress
    git clone git://github.com/almassapargali/ya-readify.git .themes/ya-readify
    rake install['ya-readify']
    rake generate

# Variables

You can modify the following variables (defined in `sass/custom/_styles.scss`):

`$accent-color`, `$accent-hover-color`, `$text-color`, `$secondary-text-color`, `$border-radius-size`, and `$hide-line-numbers` (default is `true`).

# License

The MIT License

Copyright &copy; 2013 Almas Sapargali

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
