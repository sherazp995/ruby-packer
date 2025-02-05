# frozen_string_literal: true

source 'https://rubygems.org'

ruby '3.1.2'

gem 'activesupport', '~> 6.1', '>= 6.1.7', require: 'active_support/all'
gem 'minitest', '~> 5.14', '>= 5.14.1'
gem 'minitest-reporters', github: 'kern/minitest-reporters' # make sure github gems work, cf. https://github.com/pmq20/ruby-packer/issues/95
gem 'pry', '~> 0.14.2'
gem 'rake', '~> 13.0'

# Add these gems for Ruby 3.1.2 compatibility
gem 'bundler', '~> 2.3' # Ensures compatible bundler version
gem 'json', '~> 2.6' # Required for Ruby 3.1.2
gem 'racc', '~> 1.6' # Parser generator for Ruby 3.1.2
gem 'logger', '~> 1.5' # Add explicit logger dependency