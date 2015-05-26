source 'https://rubygems.org'
gem 'rails', '4.1.8'

gem 'sass-rails', '~> 4.0.3'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jquery-turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 0.4.0',          group: :doc
gem 'bootstrap-sass' 
gem 'devise'
gem 'paperclip', github: 'thoughtbot/paperclip' 
gem 'aws-sdk', '< 2.0'
gem 'masonry-rails'
gem 'will_paginate', '~> 3.0.5'
gem 'will_paginate-bootstrap'

#Coffee script 1.9.0 doesn't play well with Windows. On my Windows 7 machine, using version 1.8.0 solved this problem.
gem 'coffee-script-source', '1.8.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin]

#Coffee script 1.9.0 doesn't play well with Windows. On my Windows 7 machine, using version 1.8.0 solved this problem.
gem 'coffee-script-source', '1.8.0'


group :development, :test do
	gem 'sqlite3'
end

group :production do
	gem 'pg'
	gem 'rails_12factor'
end