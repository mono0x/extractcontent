# ExtractContent

ExtractContent for Ruby 1.9+

## Installation

Edit Gemfile.

    $ vi Gemfile

Add a following line to Gemfile.

```ruby
gem 'extractcontent', github: 'mono0x/extractcontent'
```

Install the gem.

    $ bundle install

## Usage

```ruby
require 'bundler/setup'
require 'extractcontent'

html = ...
content, title = ExtractContent.analyse(html)

puts title
puts content
```

## License

The BSD License

The original code was written by [Nakatani Shuyo](http://labs.cybozu.co.jp/blog/nakatani/2007/09/web_1.html).

