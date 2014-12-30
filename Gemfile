source 'https://rubygems.org'

gemspec

gem 'zip'

# gem 'neo4j-advanced',   '>= 1.8.1', '< 2.0', :require => false
# gem 'neo4j-enterprise', '>= 1.8.1', '< 2.0', :require => false

gem 'coveralls', require: false
gem 'simplecov-html', require: false

group 'development' do
  gem 'pry-rescue', platform: :ruby
  gem 'pry-stack_explorer', platform: :ruby

  gem 'guard'
  gem 'guard-rspec', require: false
  gem 'guard-rubocop'
end

group 'test' do
  gem 'rake', '>= 0.8.7'
  gem 'rspec', '~> 3.0'
  gem 'rspec-its'
end
