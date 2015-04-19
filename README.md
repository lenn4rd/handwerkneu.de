# handwerkneu.de

This is the source code for my online portfolio. It's build with the excellent [Middleman](https://middlemanapp.com) static site generator.

## Getting started

In a terminal, clone this repository, `cd` into the newly created directory and install Middleman and its dependencies:

```sh
bundle install
```

Start a local server by entering `middleman`. The web site will be available at [localhost:4567](http://localhost:4567).

## Deployment

Change the deploy configuration in `config.rb` to match your setup. Afterwards, build and deploy the static files:

```sh
middleman build
middleman deploy
```