source 'https://rubygems.org'

group :development, :test do
  gem 'puppetlabs_spec_helper', :require => false
  gem 'puppet-lint', '~> 0.3.2'
  gem 'rspec-puppet', '~> 1.0.1', :require => false
  gem 'beaker-rspec', '~> 2.2.4', :require => false
  gem 'rake', '10.1.1'
  gem 'rspec', '< 2.99'
  gem 'json'
  gem 'webmock'
  gem 'minitest', :require => false
  gem 'test', :require => false
  gem 'test-unit', :require => false
end

if puppetversion = ENV['PUPPET_GEM_VERSION']
  gem 'puppet', puppetversion, :require => false
else
  gem 'puppet', :require => false
end

# vim:ft=ruby
