---
title: Make your Jekyll website
date: 2020-12-30 10:10:01 +530
categories: [Jekyll]
tags: [jekyll, website]
pin: false
---

Hey there,today we are talking about "How to make Jekyll site".

You know why we use Jekyll, if you don't read my *What is Jekyll* blog.

Ok now I thought that you have learnt what is Jekyll and what it is used for.Now follow the following steps:

## Steps:
* Check the Ruby version with `ruby -v` command.If it returns a Ruby version like `ruby 2.7` then don't worry and escape second step and follow the third step.
* If you don't get any version then run this command `sudo gem install ruby`.
This will install Ruby.

* Now run a command `sudo gem install bundler`.Bundler is a package manager that will aid you in installing all the Jekyll dependencies.

* Create a Gemfile called `Gemfile` and store that file in the folder where
you want to create your Jekyll site I am using ***welcome_jekyll*** project or folder here.
And add this `gem 'github-pages'` and this `source 'https://rubygems.org'` into Gem file and save that.

* Run `bundle install` it runs for a while.And after done it should say like: 
Bundle complete! 7 Gemfile dependencies, 31 gems now installed.

This will be the base of our 'Jekyll site'.

## Installing Jekyll
Remember the fifth step,there you runed a command called `bundle install`.That command installed Jekyll.Now I am going to call my project by running a command called `jekyll new welcome_jekyll`.Move to that directory by running `cd welcome_jekyll`

At last run `bundle exec jekyll serve` and at the end of the output you will get a link like `Server address: http://127.0.0.1:4000/lanion/` click on that with pressing control button.Then you can see your site page in your browser.

If you don't like the theme in the page and want to change it read this blog

Thank You for reading!