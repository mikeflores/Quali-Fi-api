# README

Setup (progressions)
1. Create Repo on Github 
2. Run `rails new . -d postgresql` within project folder
3. Run rails `db:create`
4. Run `rails s` to see if all is well

Write the tables by writing recipes aka migrations
1. Determine ERD 
2. Run `rails g migration create_things`
3. write the table data in the migrations file
4. write some seed data

Write the Models
1. create the models in the models folder