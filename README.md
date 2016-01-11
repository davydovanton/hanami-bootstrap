# Lotus::Bootstrap
[Bootstrap](http://getbootstrap.com/) wrapper for [lotus](http://lotusrb.org/) framework.
This wrapper provide HEAD version of bootstrap.

Also you can use [bootstrap-rubygem](https://github.com/twbs/bootstrap-rubygem) gem which support lotus framework.

## Installation
**Important:** this wrapper required jquery library.
You can use [jquery-lotus](https://github.com/Nerian/jquery-lotus) gem or add jquery.js to you assets directory.

Add this line to your application's Gemfile:

``` ruby
gem 'lotus-bootstrap'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install lotus-bootstrap

## Usage
Add bootstrap to your template:

``` erb
<%= stylesheet 'bootstrap' %>
<%= javascript 'bootstrap' %>
```

## Contributing
Bug reports and pull requests are welcome on GitHub at https://github.com/[USERNAME]/lotus-bootstrap. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.


## License
The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
