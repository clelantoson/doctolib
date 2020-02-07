# README

Ruby version 2.5.1
Rails version 5.2.4, >= 5.2.4.1

Install
git clone git@github.com/clelantoson/doctolib.git cd doctolib bundle install rails db:reset rails db:migrate rails db:seed rails c

Run (with gem 'table_print')
tp Doctor.all tp Patient.all tp Appointment.all tp City.all ...
