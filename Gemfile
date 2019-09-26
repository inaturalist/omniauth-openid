source 'http://rubygems.org'

gem 'rake', '~> 12.0'

platforms :jruby do
  gem 'jruby-openssl', '~> 0.9'
end

gem 'ruby-openid', tag: 'v2.9.0', git: 'git://github.com/openid/ruby-openid.git'

gemspec

group :development, :test do
  gem 'rack-test'
  gem 'rspec', '>= 3.0'
  gem 'simplecov', '>= 0.9'
  gem 'webmock', '~> 3.0'
  gem 'yard', '>= 0.9.11'
end

group :example do
  gem 'sinatra'
end
