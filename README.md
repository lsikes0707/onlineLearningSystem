# Online Learning System
# Created the scheduler:
- rails new scheduler
- cd scheduler/
- rails g controller home index
# may need to run: 
- rails webpacker:install
- rails db:migrate
# may also need to remove '<%= javascript_pack_tag 'application', 'data-turbolinks-track': 'reload' %>' from: the application.html.erb in app/views/layouts

Modify the Gemfile in directory to reflect the source code on this repo.

# You may also fin userful in finding Ruby gems and what they are for:
- https://rubygems.org/
