source "https://rubygems.org"

gemspec

gem "rails", "~> 4.2.6"
gem "omniauth"
gem "omniauth-oauth2"
gem "rdoc"

group :test do
  gem "omniauth-facebook"
  gem "omniauth-openid"
  gem "webrat", "0.7.3", require: false
  gem "mocha", "~> 1.1", require: false
  gem 'test_after_commit', require: false
end

platforms :jruby do
  gem "activerecord-jdbc-adapter"
  gem "activerecord-jdbcsqlite3-adapter"
  gem "jruby-openssl"
end

platforms :ruby do
  gem "sqlite3"
end

group :mongoid do
  gem "mongoid", "~> 5.0"
end
