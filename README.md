This repository contains the source of the [JabCon homepage](http://jabref.github.io/JabCon/).
Feel free to improve the page or ask a public questions using the [issue tracker](https://github.com/JabRef/JabCon/issues).

Execute `gem install bundler`, `bundle install`, and `bundle exec jekyll serve` to serve this page locally at http://localhost:4000/JabCon/.
Source: https://help.github.com/articles/using-jekyll-with-pages/#installing-jekyll
Note that browsing the pages does not work locally before Jekyll 3.0, because [Jekyll 2.x cannot deal with URLs indirectly pointing to .html](https://github.com/jekyll/jekyll/pull/3452).

At windows, serving with Jekyll works with [RubyInstaller](http://rubyinstaller.org/downloads) and the [Development Kit](https://github.com/oneclick/rubyinstaller/wiki/Development-Kit).
[JRuby](http://jruby.org/) doesn't work as the [C extensions were dropped](http://stackoverflow.com/a/32135381/873282).
