# udemy-the-complete-ror-dev-course
The Complete Ruby on Rails Developer Course (Udemy)
https://www.udemy.com/the-complete-ruby-on-rails-developer-course/


https://github.com/rubocop-hq/ruby-style-guide
https://github.com/bbatsov/ruby-style-guide

https://gorails.com/setup/ubuntu/18.04
sudo service postgresql start

rails new myapp -d postgresql

cd /mnt/d/RubyOnRails/udemy-the-complete-ror-dev-course

rails generate scaffold Article title:string description:string
rails destroy scaffold Article

//view debugger
<%= debug(params) if Rails.env.development? %>
//potential placeholder for a controller method
render plain: params[:article].inspect



//ruby 2.3.5
sudo apt purge libssl-dev && sudo apt install libssl1.0-dev