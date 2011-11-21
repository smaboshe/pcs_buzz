# pcs_bootstrap

## Preamble

`pcs_bootstrap` is a gem that packages the asset files used in Jay Salvat's [Buzz HTML5 Audio Javascript library](http://buzz.jaysalvat.com/).


## Setup

In a Rails 3.1.x project add the gem to your assets group in your `Gemfile`. It is currently in pre-release:

	gem "pcs_buzz", "~> 0.0.1.alpha"

Bundle the gem using bundler:

	bundle

Once your bundle is updated, you can automatically add the assets to your CSS and Javascript manifest files using the generator:

	rails generate buzz:install

Alternatively, you can manually require the Javascript assets by adding:

	//= require buzz

to your `application.js`

You may need to restart your application for the changes to reflect (I find this behaviour a bit odd and am looking in to why).

## Usage

Once the setup is complete, you'll be able to use the plugin. You can learn more about it from the [official website](http://buzz.jaysalvat.com/).

Enjoy!
