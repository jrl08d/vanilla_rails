source 'https://rubygems.org'
is_java = RUBY_PLATFORM =~ /java/

gem 'rails', '3.2.20'

if is_java
  gem 'activerecord-jdbc-adapter', '1.3.19'
  gem 'activerecord-jdbcpostgresql-adapter', '1.3.19'
  gem 'jruby-rack', '1.1.14'
  gem 'jruby-jars', '1.7.22'
  gem 'jruby-pageant', '1.1.1'
  gem 'jruby-pgp'
  gem 'jruby-openssl', '0.9.12'
else
  gem 'pg'
end

gem 'sass-rails'
gem 'uglifier'
gem 'coffee-rails'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder'
