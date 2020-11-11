Agency Jekyll theme
====================

## Installation

### Install Environment Manager for Ruby
`brew install rbenv ruby-build`

### bash
```
echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.bash_profile
echo 'eval "$(rbenv init -)"' >> ~/.bash_profile
```  

### zsh
```
echo 'export PATH="$HOME/.rbenv/bin:$PATH"' >> ~/.zprofile
echo 'eval "$(rbenv init -)"' >> ~/.zprofile  
```

### Install openssl
`brew install openssl`

`export RUBY_CONFIGURE_OPTS="--with-openssl-dir=$(brew --prefix openssl@1.1)" .. ~/.zshrc`

### list all available versions:
`rbenv install -l`

### install a Ruby version:
`rbenv install 2.4.1`

### set ruby version for a specific dir
`rbenv local 2.4.1`

### set ruby version globally
`rbenv global 2.4.1`

`rbenv rehash`

## Staring Jekyll

```
gem install bundler jekyll
bundle exec jekyll serve
```

# How to use

###Portfolio 

Portfolio projects are in '/_posts'

Images are in '/img/portfolio'

###About

Images are in '/img/about/'

###Team

Team members and info are in '_config.yml'

Images are in '/img/team/'


# Demo

View this jekyll theme in action [here](https://y7kim.github.io/agency-jekyll-theme)

=========
For more details, read [documentation](http://jekyllrb.com/)

Agency theme based on [Agency bootstrap theme ](https://startbootstrap.com/template-overviews/agency/)