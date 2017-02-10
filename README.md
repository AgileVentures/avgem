# avgem

avgem wraps the Bootstrap 4 library in a rails along with AV assets into an
engine for simple use with the asset pipeline provided by Rails 5 and higher.
The gem includes the development (non-minified) source for ease of exploration.
The asset pipeline will minify in production.

## Usage

Add the following to your gemfile:

    gem 'avgem'

Add the following directive to your Javascript manifest file (application.js):

    //= require bootstrap 

Add the following to application.css:

    @import "bootstrap";

If you have problems, refer to the following:

    https://rubyplus.com/articles/3981-Integrating-Twitter-Bootstrap-4-with-Rails-5

## Versioning

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'avgem'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install avgem

## Usage

TODO: Write usage instructions here

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `rake spec` to run the tests. You can also run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release`, which will create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/avgem.

