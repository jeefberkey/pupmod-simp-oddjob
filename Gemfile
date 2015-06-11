source 'https://rubygems.org'

puppetversion = ENV.key?('PUPPET_VERSION') ? "#{ENV['PUPPET_VERSION']}" : ['~>3']
gem 'puppet', puppetversion
gem 'puppet-lint'
gem 'puppetlabs_spec_helper'
gem 'puppet_module_spec_helper'
gem 'simp-rake-helpers'

group :debug do
    gem 'pry'
    gem 'pry-doc'
    gem 'rspec'
    gem 'mocha'
    gem 'metadata-json-lint'
end
