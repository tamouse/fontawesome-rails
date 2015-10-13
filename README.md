# Fontawesome::Rails

[The amazing Fontawesome](http://fontawesome.io) packaged for Rails Asset Pipeline.

**NOTE:** This fork removes the egregious `require 'pry'` left in the railtie.

## Installation

Add this line to your Rails application's Gemfile:

    gem 'fontawesome-rails', github: 'tamouse/fontawesome-rails'

And then execute:

    $ bundle

## Usage

Just require fontawesome in your application.css

    //= require 'fontawesome'

If you are using SASS

    @import "fontawesome"

Add CSS classes to DOM elements e.g. class='fa fa-bookmark'. [See all icons](http://fontawesome.io/icons/)

## Troubleshooting

Restart your Rails application.

Assets might get cached, removing `//=require "fontawesome"`, refreshing and adding it back in might help.

## Versioning

The gem follows Fontawesome versioning conventions e.g. if you need `4.0.3` version of fontawesome
it will be available in fontawesome-rails '~> 4.0.3.X'

## Contributing

1. Fork it ( http://github.com/tamouse/fontawesome-rails/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
