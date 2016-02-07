# Hanami::Bootstrap
[Bootstrap](http://getbootstrap.com/) wrapper for [hanami](http://hanamirb.org/) framework.
This wrapper provide HEAD version of bootstrap.

Also you can use [bootstrap-rubygem](https://github.com/twbs/bootstrap-rubygem) gem which support hanami framework.

## Installation
**Important:** this wrapper required jquery library.
You can use [jquery-lotus](https://github.com/Nerian/jquery-lotus) gem or add jquery.js to you assets directory.

Add this line to your application's Gemfile:

``` ruby
gem 'hanami-bootstrap'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install hanami-bootstrap

## Usage
Add bootstrap to your template:

``` erb
<%= stylesheet 'bootstrap' %>
<%= javascript 'bootstrap' %>
```

## Contributing
Bug reports and pull requests are welcome on GitHub at https://github.com/davydovanton/hanami-bootstrap. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.


## License
The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
