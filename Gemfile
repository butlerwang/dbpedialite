source "http://rubygems.org"
ruby "1.9.3"

gem 'thin'

gem 'sinatra'
gem 'sinatra-contrib', :require => 'sinatra/content_for'
gem 'emk-sinatra-url-for', :require => 'sinatra/url_for'

gem 'json_pure', :require => 'json'
gem 'nokogiri'
gem 'rdiscount'
gem 'doodle'

gem 'rdf', ">=0.3.1"
gem 'rdf-json', :require => 'rdf/json'
gem 'rdf-turtle', :require => 'rdf/turtle'
gem 'rdf-trix', :require => 'rdf/trix'
gem 'rdf-rdfxml', :github => 'ruby-rdf/rdf-rdfxml', :branch => 'master', :require => 'rdf/rdfxml'
gem 'json-ld', :github => 'ruby-rdf/json-ld', :branch => 'develop', :require => 'json/ld'

group :development do
  gem 'rake'
  gem 'shotgun'
end

group :test do
  gem 'rspec', '>=2.7.0'
  gem 'fakeweb'
  gem 'simplecov'
  gem 'rack-test', :require => 'rack/test'
  gem 'rdf-rdfa', :require => 'rdf/rdfa'
  gem 'equivalent-xml'
end
