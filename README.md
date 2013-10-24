# PacejsRails

Pace.js (Automatic web page progress bar) for Rails 3.1 and up (including 4) to work with the asset pipeline to provide versioning of the code

as seen https://github.com/HubSpot/pace

## Installation

Add this line to your application's Gemfile:

    gem 'pacejs_rails'


Add the following directive to your Javascript manifest file (application.js):

    //= require pace

In the stylesheet manifest (application.css) add a theme of your choosing:

for exmaple

    *= pace-theme-big-counter

see themes here: http://github.hubspot.com/pace/docs/welcome/

themes available: https://github.com/HubSpot/pace/tree/master/themes


And then execute:

    $ bundle

Or install it yourself as:

    $ gem install pacejs_rails

## Usage

just install and it will monitor all ajax requests and stuff 
## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
