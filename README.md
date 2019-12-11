# Prerequisites #

To start using Travis CI, make sure you have:

    1. A GitHub account.
    2. Owner permissions for a project hosted on GitHub.

To get started with Travis CI #

    1. Go to Travis-ci.com and Sign up with GitHub.
    2. Accept the Authorization of Travis CI. You’ll be redirected to GitHub.
    3. Click on your profile picture in the top right of your Travis Dashboard,click the green Activate button, and select the repositories you want to use with Travis CI.
    4. Add a .travis.yml file to your repository to tell Travis CI what to do.
    5. The following example specifies a Ruby project that should be built with Ruby 2.2 and the latest versions of JRuby.

vim .travis.yml

language: ruby
rvm:
 - 2.2
 - jruby

    6. Add the .travis.yml file to git, commit and push to trigger a Travis CI build:
    7. Check the build status page to see if your build passes or fails according to the return status of the build command by visiting Travis CI and selecting your repository.
