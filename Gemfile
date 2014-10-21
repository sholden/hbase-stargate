source :rubygems

gemspec

gem "faraday"
gem 'rake'

platforms :ruby do
  gem "yajl-ruby"
end

platforms :jruby do
  gem "json"
end

group :test do
  gem "rspec", '~>2.99.0'
  # gem 'ruby-debug19', :require => 'ruby-debug'
end
