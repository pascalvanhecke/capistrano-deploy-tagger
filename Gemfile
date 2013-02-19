source "http://rubygems.org"

gemspec

group :development do
  gem 'guard'
  gem 'guard-rspec'
  gem 'rb-fsevent', '~> 0.9.1'      # to improve guard performance

  # if you do not want Growl on your machine, run "bundle --without growl"
  # once and the gems in this group will be ignored for every following bundle
  if RUBY_PLATFORM.include?('darwin')
    group :growl do
      gem 'growl'
      gem 'growl_notify'
    end
  end
end