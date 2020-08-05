# The Gilded Rose Code Kata

This is a Ruby version of the Gilded Rose Kata, found
[here](http://iamnotmyself.com/2011/02/13/refactor-this-the-gilded-rose-kata/).

This is a refactorying kata, so you will be starting with a legacy
code base.  To work the Kata, clone this git repository and checkout
the tag 'start-here'. Read the description below for the "rules"
involving this kata.

## Changes from the original

This Ruby version follows the original code very closely, but has the
following changes:

* The original had no tests.  Since this is a refactoring kata, I feel
  the tests are important and provide a fairly complete test suite.
  Just delete the tests if you wish to "go it alone".

* The original used a hard coded set of "items", presumably for
  testing the code.  Since I added a test suite, the hard coded values
  were not of much use.  I also changed the interface to accept a list of
  items as a parameter rather than a hard coded constant.

You can read
[the original kata article](http://iamnotmyself.com/2011/02/13/refactor-this-the-gilded-rose-kata/) for more details.

## Installation Hints

The easiest way is to use bundler to install the dependencies. To do so, you need to install the bundler gem if you haven't already done so

    gem install bundler

run bundler

    bundle

and should be ready to go. Alternatively, you can install the dependencies one by one using gem install, e.g.

    gem install rspec-given

Have a look at the Gemfile for all dependencies.