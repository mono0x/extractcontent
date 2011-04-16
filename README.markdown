# ExtractContent

ExtractContent for Ruby 1.9

## Installation

Install bundler.

    gem install bundler
    bundle init
    vi Gemfile

Add the following line to Gemfile.

    gem 'extractcontent', :git => 'https://github.com/mono0x/extractcontent.git'

Install the gem.

    bundle install

## Usage

    # coding: utf-8

    require 'bundler/setup'
    require 'extractcontent'

    html = ...
    content, title = ExtractContent.analyse(html)

    puts title
    puts content

## License

The BSD License

The original code was written by [Nakatani Shuyo](http://labs.cybozu.co.jp/blog/nakatani/2007/09/web_1.html).

