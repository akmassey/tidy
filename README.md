# Aaron Massey's HTML Tidy configuration

Similar to [my vim configuration][1], I'm now managing my [tidy
configuration][2] file [using stow][3].

    .
    ├── .tidyrc
    ├── LICENSE.md
    └── README.md

If you wanted to do the same, don't forget to ignore the readme when you
deploy it:

    stow --ignore "README.md|LICENSE.md" tidy

You may also need to set an environment variable for the configuration file to
be recognized:

    export HTML_TIDY=$HOME/.tidyrc

I'm happy to share, just let me know what you think.


[1]: https://github.com/akmassey/vim
[2]: http://tidy.sourceforge.net/
[3]: http://brandon.invergo.net/news/2012-05-26-using-gnu-stow-to-manage-your-dotfiles.html
