source 'https://rubygems.org'

gem 'mysql-pr', '~> 2.9', git: 'https://github.com/denistsuman/mysql-pr' # fixed encoding
gem 'postgres-pr', '~> 0.7'
gem 'rake', '~> 12.0'

platforms :jruby do
  gem 'activerecord'
  gem 'activerecord-jdbc-adapter'
  gem 'activerecord-jdbcpostgresql-adapter'
  gem 'jdbc-postgres'
end

platforms :mri do
  gem 'pg', '~> 0.18'
end

gem 'test-unit'

group :test do
  gem 'jeweler', '~> 2.0'
end
