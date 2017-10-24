source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.1.1'
# Use postgresql as the database for Active Record
gem 'pg', '~> 0.18'
# Use Puma as the app server
gem 'puma', '~> 3.7'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'
gem 'aws-sdk', '>= 2.0'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

gem 'spree', '~> 3.3'
gem 'spree_auth_devise', '~> 3.3'
gem 'spree_gateway', '~> 3.3'
gem 'kiba'

gem 'spree_active_shipping', github: 'spree-contrib/spree_active_shipping'
gem 'active_shipping'

gem 'spree_i18n', github: 'spree-contrib/spree_i18n', branch: 'master'

gem 'spree_account_recurring', github: 'javogel/spree-account-recurring'

gem 'spree_multi_currency', github: 'spree-contrib/spree_multi_currency'
gem 'spree_multi_domain', github: 'spree-contrib/spree-multi-domain'
#gem 'spree_product_assembly', github: 'markbiegel/spree-product-assembly', branch: '3-2-stable'
gem 'spree_static_content', github: 'spree-contrib/spree_static_content'
gem 'spree_print_invoice', github: 'spree-contrib/spree_print_invoice', branch: 'master'
gem 'spree_editor', github: 'spree-contrib/spree_editor'
gem 'tinymce-rails-langs'
gem 'mysql2'
gem 'zoho-subscriptions'
gem 'spree_custom_checkout', github: 'YanivRan/Spree-Custom-Checkout'
gem 'spree_admin_roles_and_access', '3.2.1.beta', github: 'YanivRan/spree_admin_roles_and_access'
gem 'pdf-reader'


group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '~> 2.13'
  gem 'selenium-webdriver'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
