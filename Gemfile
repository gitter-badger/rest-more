
source 'https://rubygems.org/'

gemspec

# this is for travis-ci
gem 'rest-core', :path => 'rest-core' if
  File.exist?("#{File.dirname(File.expand_path(__FILE__))}/rest-core/Gemfile")

gem 'rest-client'
gem 'em-http-request'

gem 'rake'
gem 'bacon'
gem 'muack'
gem 'webmock'

gem 'json'
gem 'json_pure'
gem 'multi_json'

gem 'rack'
gem 'ruby-hmac'

platforms(:ruby) do
  gem 'yajl-ruby'
end

platforms(:jruby) do
  gem 'jruby-openssl'
end

gem 'rails', '3.2.13' if ENV['RESTMORE'] == 'rails3'
