# JSON formatter for SimpleCov

***Note: To learn more about SimpleCov, check out the main repo at [SimpleCov](https://github.com/simplecov-ruby/simplecov)***

Generates a formatted JSON report of your [SimpleCov](https://github.com/simplecov-ruby/simplecov) ruby code coverage results on ruby 2.4+. Originally intended to add `simplecov`'s results reading capacity to CI tools.

## Overview

You can expect for this gem to produce a `coverage.json` file, located at the `coverage` folder.

Depending on your `SimpleCoV`'s settings you will experiment different outcomes. Particularly depending on which type of coverage are you running `SimpleCov` with:

- If you configure `SimpleCov` to run with `branch` coverage you should expect an output formatted like [sample_with_branch.json](https://github.com/codeclimate-community/simplecov_json_formatter/blob/master/spec/fixtures/sample_with_branch.json)
- Otherwise you should expect an output formatted like [sample.json](https://github.com/codeclimate-community/simplecov_json_formatter/blob/master/spec/fixtures/sample.json)

## Development

### Setup

Run `bundle install` to install dependencies needed for local development.

### Tests

`bundle exec rspec` will trigger the excution of running tests.

## Copyright

See [License](https://github.com/codeclimate-community/simplecov_json_formatter/blob/master/LICENSE)
