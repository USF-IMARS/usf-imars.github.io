This workflow is useful for making bigger changes or testing changes before committing.
It requires a linux machine able to install & run jekyll.

Setup adapted from [jekyll quickstart docs](https://jekyllrb.com/docs/):


1. Install a full [Ruby development environment](https://jekyllrb.com/docs/installation/).
    * on manjaro: `sudo pacman -Sy ruby base-devel libffi`
2. Install Jekyll and bundler gems.
    `gem install jekyll bundler`
3. clone to local machine
    `git clone git@github.com:USF-IMARS/usf-imars.github.io.git`
4. Change into your project directory.
    `cd usf-imars.github.io`
5. install dependencies
    `bundle install`
6. Build the site and make it available on a local server.
    `bundle exec jekyll serve`
7. Browse to http://localhost:4000
