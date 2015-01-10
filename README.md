## Zeppelin project website


## Build
See https://help.github.com/articles/using-jekyll-with-pages#installing-jekyll

**tl;dr version:**

    ruby --version >= 1.9.3
    gem install bundler
    bundle install
    
*On OS X 10.9 you may need to do "xcode-select --install"*

## On local machine

### Run
    bundle exec jekyll serve --watch

### Deploy
Simply commit gh-pages and Github will do the actuall job of generating static HTML pages

### Add a new page
    rake page name="new-page.md"
    
