# StyleElmatica

Elmatica shared Rubocop rules

## Installation

Add this line to your application's Gemfile:

```ruby
group :test, :development do
    gem 'style_elmatica'
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
    elmatica_style:
        - default.yml
```
