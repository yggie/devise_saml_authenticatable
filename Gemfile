source 'https://rubygems.org'

# Specify your gem's dependencies in devise_saml_authenticatable.gemspec
gemspec

group :test do
  gem 'rake'
  gem 'rspec', '~> 3.0'
  gem 'rails', '~> 5.0'
  gem 'rspec-rails'
  gem 'sqlite3'
  gem 'capybara'
  gem 'poltergeist'

  # Lock down versions of gems for older versions of Ruby
  if Gem::Version.new(RUBY_VERSION.dup) < Gem::Version.new("2.0")
    gem 'mime-types', '~> 2.99'
  end
  if Gem::Version.new(RUBY_VERSION.dup) < Gem::Version.new("2.1")
    gem 'devise', '~> 3.5'
  end
end
