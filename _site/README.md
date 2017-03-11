# My personal "front" webpage

# Credits

Theme: based on <a href="https://github.com/dashingcode">@dashingcode</a>'s <a href="https://github.com/dashingcode/front-cover">Font Cover Jekyll theme</a> under the MIT license, for <a href="http://jekyllrb.com/">Jekyll</a> on <a href="http://pages.github.com/">GitHub Pages</a>.

The Font Cover Jekyll theme makes use of both the <a href="http://fontawesome.io/">Font Awesome</a> icons and the <a href="http://jpswalsh.github.io/academicons/">Academicons</a> icons.

# Installation and pre-visualization

## Installation

```shell
sudo apt-get install ruby ruby-dev
echo "PATH=\"$(ruby -e 'print Gem.user_dir')/bin:$PATH\"" >> ~/.bashrc 
gem install jekyll bundler --user-install
bundle install
```

## Pre-visualization before deployment

```shell
jekyll serve
```

In a web browser, access the web page at `127.0.0.1:4000`