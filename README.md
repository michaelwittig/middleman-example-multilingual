# Middleman Example: multilingual website

This example shows how you can create a multilingual website with https://middlemanapp.com. This example was tested with version 3.3.10.

## How multilingual works

### locales

You can translate words and sentences that you want to use in multiple languages with locales. Each language can be found in the locales directory.

### *.{de, en}.html.erb files

If you want to translate a whole page use files than end with .de.html.erb or .en.html.erb.

## Run example

First you need to [install Middleman](https://middlemanapp.com/basics/install/).

Then execute the following command in the repository's folder

	bundle exec middleman server

* Open http://localhost:4567/en to see the english version of the page.
* Open http://localhost:4567/de to see the german version of the page.

A language switcher is available in the upper-right.

## Build example

To create all the static stuff that you need to upload the website to your favorite hosting company run

	bundle exec middleman build

You will find a newly created build directory.
