# The Bluehive email template tool
## Introduction
This is a tool used to build HTML and text templates for Ford emails
This script is meant to help Bluehive update media on the Brightcove Video Cloud platform
## Requirements
### Homebrew
If you don't have [Homebrew](http://brew.sh), we recommend you installit it. Homebrew is the missing package manager for OS X.
````
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
````
### Ruby
````
brew install rbenv ruby-build

# Add rbenv to bash so that it loads every time you open a terminal
echo 'if which rbenv > /dev/null; then eval "$(rbenv init -)"; fi' >> ~/.bash_profile
source ~/.bash_profile

# Install Ruby
rbenv install 2.2.2
rbenv global 2.2.2
ruby -v
````
### Rails
````
gem install rails -v 4.2.1
rbenv rehash
rails -v
# Rails 4.2.1
````
## Installation
````
# clone repo
git clone git@github.com:greatcarrot/middleman.git

# enter repo
cd middleman

# install dependencies - this might not be possible without a VPN
bundle install
````
## Git
Each time a change is made to the code, we should commit it to Github. Use these commands.
````
# add changes to git
git add -A

# commit changes to git
git commit -m "your message goes here"

# push changes to bitbucket
git push
````
Before you start working, make sure you are always working on latest version by using this command
````
# pull changes from bitbucket
git pull
````

## Run the Script
From the console, run this command
````
middleman build
````
This will run the build process and put all final files in the `/build` folder