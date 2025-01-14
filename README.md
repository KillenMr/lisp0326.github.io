## Overview

This is the github repo for the Yi's lab [website](http://lisp0326.github.io). The website uses the static site generator [jekyll](https://jekyllrb.com/) and is based on the [Feeling Responsive jekyll theme](https://github.com/Phlow/feeling-responsive) and [Griffith lab theme](https://griffithlab.org/). Development occurs on the dev branch, the live site is located on the master branch.

## Installation

To install this site locally run the following commands:

1. Clone the repo and cd into it `$ git clone git@github.com:griffithlab/griffithlab.github.io.git`
2. Install the bundler `$ gem install bundler`
3. Install gems `$ bundle install`
4. run jekyll and watch for changes `$ bundle exec jekyll serve --config _config.yml,_config_dev.yml --watch`

The site should now be running on localhost port 4000. Changes to files will show up interactively on localhost:4000

**Note:** The _config.yml file is only read during the initial serve, changing this file will require re-running step 4 for changes to appear.

## License

The code for this site is licensed under an MIT license, images may have specific attribution requirements and are licensed individually under assets/img/image_attribution
