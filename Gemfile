source 'https://rubygems.org'
ruby '2.3.3'

gem 'sinatra', '~> 1.4', '>= 1.4.7'
gem 'datamapper', '~> 1.2'
gem 'json', '~> 1.8', '>= 1.8.3'

group :development, :test do
    gem "sqlite3"
    gem 'dm-sqlite-adapter'
    gem 'rerun', '~> 0.11.0'
end

group :production do
    gem "pg"
    gem "dm-postgres-adapter", '~> 1.2'
end
