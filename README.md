# Sample

The sample gem provides no functionality. It is just enough of a package to be useful for testing software that uses gems.

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'sample'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install sample

## Usage

You could then prove that the correct version of the gem is installed as follows:

```
sheldonh@DESKTOP-EL62KQG:~/sample-gem$ irb
3.4.1 :001 > $LOAD_PATH.unshift('lib');
3.4.1 :002 > require 'sample';
3.4.1 :003 > Sample::VERSION
 => "0.1.2"
```

Most likely, you already have your own test methods and just needed an off-the-shelf gem on RubyGems.

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/starjuice/sample-gem.

