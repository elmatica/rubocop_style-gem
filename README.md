# StyleElmatica

Elmatica shared Rubocop rules

## Installation

Add this line to your application's Gemfile:

```ruby
group :test, :development do
    gem "style_elmatica", github: "elmatica/rubocop_style-gem"
end
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install style_elmatica

## Usage

Create a `.rubocop.yml` with the following directives:

```ruby
inherit_gem:
    style_elmatica:
        - default.yml
```

Then run `rubocop` as:

    $ bundle exec rubocop
