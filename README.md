# Overview
This repository hosts the MIT Anime Club's club website, hosted at anime.mit.edu. The club website is a static site generated using Jekyll and is served using GitHub Pages.

# Making changes to the site
To make changes to this site, it is recommended you first check that your change works locally. Once you have verified that your change works locally, you can push your change to the master branch on GitHub. Your changes will be deployed to anime.mit.edu.

## How to verify changes locally
1. [Install ruby](https://www.ruby-lang.org/en/documentation/installation/#homebrew). If you are on MacOS, twang6 recommends installing via Homebrew. Ruby is what Jekyll is written in.
2. Install [bundler](https://bundler.io/) by running the command `gem install bundler`. Bundler helps manage ruby dependencies for projects.
3. Navigate to the git repository directory on your computer and run the command `bundle install`. This installs the dependencies for this project.
4. Launch a local copy of the site by running the command `bundle exec jekyll serve`. This runs Jekyll using the dependencies installed by bundle and has Jekyll serve a local copy of the site. By default, the local site can be viewed at http://localhost:4000.
5. Check to see that your changes are showing up properly locally. If they are you can commit your changes and push them to GitHub.
