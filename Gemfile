source 'http://rubygems.org'

gem 'rails', '3.1.0'

# Bundle edge Rails instead:
# gem 'rails',     :git => 'git://github.com/rails/rails.git'

gem 'sqlite3'

#Dodajemo gemove za Rspec i Rspec library, zbog testiranja

group :development do
  gem 'rspec-rails', '2.6.1'
  gem 'rails', '3.1.0'
  gem 'sqlite3', :group => :development
end     

group :test do 
  gem 'rspec-rails', '2.6.1'
  gem 'webrat', '0.7.1'
  gem 'autotest','4.4.6'
  gem 'autotest-rails-pure', '4.1.2'
  gem 'autotest-growl', '0.2.9'
end

group :production do
  #Gemovi za Heroku 
  gem "pg"
end

group :development, :test do
  gem 'sqlite3'
end


