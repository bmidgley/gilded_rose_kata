# The Gilded Rose Code Kata

[![Build Status](https://travis-ci.org/plainprogrammer/gilded_rose_kata.svg?branch=master)](https://travis-ci.org/plainprogrammer/gilded_rose_kata)

This is a refactoring kata, so you will be starting with a legacy
code base.  To work this kata, clone this repo and checkout `master` before
pulling off a new branch to begin your work. Once you have your branch ready to
work on, run `bin/rake` or `rspec spec/` to confirm your stating point is
clean. As you make your refactorings, ensure you are running the test suite
with the previously mentioned commands to ensure correctness.

<hr />

# The Gilded Rose

Hi and welcome to team Gilded Rose. As you know, we are a small inn
with a prime location in a prominent city run by a friendly innkeeper
named Allison. We also buy and sell only the finest
goods. Unfortunately, our goods are constantly degrading in quality as
they approach their sell by date. We have a system in place that
updates our inventory for us. It was developed by a no-nonsense type
named Leroy, who has moved on to new adventures. Your task is to add
the new feature to our system so that we can begin selling a new
category of items. First an introduction to our system:

- All items have a SellIn value which denotes the number of days we
  have to sell the item
- All items have a Quality value which denotes how valuable the item
  is
- At the end of each day our system lowers both values for every item

<hr />

## Installation Hints

The easiest way is to use bundler to install the dependencies. To do so, you need to install the bundler gem if you haven't already done so

    gem install bundler

run bundler

    bundle

Have a look at the Gemfile for all dependencies.

## Git Branches

* The `master` branch contains the starting point for the kata.
* The `solution1` branch is Jim Weirich's first solution for this kata.

## Changes from the original

This Ruby version follows the original code very closely, but has the
following changes:

* The original had no tests.  Since this is a refactoring kata, I feel
  the tests are important and provide a fairly complete test suite. (Jim Weirich)

* The original used a hard coded set of "items", presumably for
  testing the code.  Since I added a test suite, the hard coded values
  were not of much use.  I also changed the interface to accept a list of
  items as a parameter rather than a hard coded constant. (Jim Weirich)

You can read
[the original kata article](http://iamnotmyself.com/2011/02/13/refactor-this-the-gilded-rose-kata/) for more details.
