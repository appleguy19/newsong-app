[![Netlify Status](https://api.netlify.com/api/v1/badges/db5cf739-7b26-4b8f-a6bd-82b979ff3b06/deploy-status)](https://app.netlify.com/sites/newsong-app/deploys)

# About

This is a microsite, only accessible from within the Newsong App (Subsplash).


### For Developers

To work on the Newsong website you should be familiar with the following technologies:

 - The command line
 - Yarn
 - Git
 - Jekyll (especially Liquid templating)
 - HTML
 - SCSS
 - JavaScript

#### Grab the Code

0. Install and [configure Git](https://help.github.com/articles/set-up-git/)

0. [Set up an SSH key](https://help.github.com/articles/generating-ssh-keys/)

0. Clone the repository: `git clone git@github.com:appleguy19/newsong-app.git`

#### Set up Software

0. In this directory run `bundle install`

### Local Development

Because this project has a Gemfile, all you need to do is run `bundle exec jekyll serve` to build the site.

### Updating & deploying this website

0. Create a branch.

0. Commit changes to that branch.

0. Create a Pull Request (into `master`). Remember to reference a Github Issue if there is one.

0. Merge into `master`.

0. The site will be automatically deployed via [Netlify](https://netlify.com) to https://newsong-app.netlify.com
