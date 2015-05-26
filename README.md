## Tag Bearer ![Travis CI](https://travis-ci.org/danjellesma/tag_bearer.svg?branch=master "Build Status") [![Code Climate](https://codeclimate.com/github/danjellesma/tag_bearer/badges/gpa.svg)](https://codeclimate.com/github/danjellesma/tag_bearer)[![Test Coverage](https://codeclimate.com/github/danjellesma/tag_bearer/badges/coverage.svg)](https://codeclimate.com/github/danjellesma/tag_bearer/coverage)

A gem that handles tags in a "Key"/"Value" setup.

We've been using acts_as_taggable_on for a lot of projects, and if all you need are single tags, it's a great solution. But similar to AWS we needed a solution that allowed us to use Keys and Values, and Tag Bearer was born. 

Setup is simple 

``` bash
gem install tag_bearer
```

This will create a migration for you to create the database table needed to house the tags.

Awesomeness!