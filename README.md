# BigBrothers Network
Interact with Facebook posts to earn tokens and use tokens to earn more interaction on Facebook posts

## Disclaimer
This is an ongoing project, and this repository is barely an MVP. For security reasons, some features of the app is not available in the public repository.

## Table of Contents:
- [Features](#how-to-use)
- [Deployment](#deployment)
- [Technologies Used](#technologies-used)
- [Contributors](#project-maintainers)
## Features
### Homepage of all currently Active Posts
<p align="center">
  <kbd>
<img src="https://user-images.githubusercontent.com/60612625/194976358-64044226-c614-4aa3-b255-44cca19c6646.png"></img>
  </kbd>
</p>

### Profile page directly linked to facebook account
<p align="center">
  <kbd>
<img src="https://user-images.githubusercontent.com/60612625/194976412-d943fc48-ed34-4e3f-a615-98919e55ec81.gif"></img>
  </kbd>
</p>

### Postnow Page

<p align="center">
  <kbd>
<img src="https://user-images.githubusercontent.com/60612625/194976909-4862f57d-2d05-4edc-acfd-4151ce9ceab4.png"></img>
  </kbd>
</p>

## Deployment:

In order to deploy the website, you will need to have Jekyll installed on your computer. Jekyll is a very excellent static-web template builder. Full documentations on Jekyll can be found [here](https://jekyllrb.com/docs/installation/windows/)

To install Jekyll, we need to download and install a `Ruby+Devkit` version from [RubyInstaller Downloads](https://rubyinstaller.org/downloads/). Use default options for installation.

After that, install Jekyll and Bundler using `cmd` by typing `gem install jekyll bundler`. Type `jekyll -v` to check the version of jekyll installed.

This website is also hosted using github website. On how to create a github website with jekyll, I find [this video](https://www.youtube.com/watch?v=fqFjuX4VZmU) exceptionally helpful, and I personally followed Mike's instruction when I first started blogging.

Briefly explained, you first have to go to your repository `Setting` on github, and change your `Page` settings to `Deploy from a branch`. (GitHub has made site deployment much easier recently), and configure the source in your `config.yml` file.

## Technologies Used:
- JavaScript
- NodeJS
- OAuth
- Facebook Passport
- Websocket
- MongoDB
## Contributiors:
- Thanks to my dearest project partner Nguyen Ha Duy from École Polytechnique.
