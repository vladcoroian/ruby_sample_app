source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

gem 'rails'                      
gem 'image_processing'            
gem 'mini_magick'            
gem 'coffee-rails'
gem 'active_storage_validations'  
gem 'bcrypt'                      
gem 'faker'                       
gem 'will_paginate'               
gem 'bootstrap-will_paginate'     
gem 'bootstrap-sass'              
gem 'puma'                        
gem 'sass-rails'                  
gem 'webpacker'                   
gem 'turbolinks'                  
gem 'jbuilder'
gem 'jquery-rails'
gem 'bootsnap',                     require: false

group :development,  :test do
  gem 'sqlite3'  
  gem 'byebug',     platforms: [:mri , :mingw  ,:x64_mingw]
end

group :development do
  gem 'web-console'            
  gem 'listen'                 
  gem 'spring'                 
  gem 'spring-watcher-listen'  
end

group :test do
  gem 'capybara'                  
  gem 'selenium-webdriver'        
  gem 'webdrivers'                
  gem 'rails-controller-testing'  
  gem 'minitest'                  
  gem 'minitest-reporters'        
  gem 'guard'                    
  gem 'guard-minitest'            
end

group :production do
  gem 'pg'          
  gem 'aws-sdk-s3' ,   require: false
end

# Windows does not include zoneinfo files  so bundle the tzinfo-data gem
# Uncomment the following line if you're running Rails
# on a native Windows system:
# gem 'tzinfo-data'  platforms: [:mingw  :mswin  :x64_mingw  :jruby]