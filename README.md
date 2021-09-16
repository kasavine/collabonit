# README


Things you may want to cover:

* Ruby version - 

* System dependencies - 

* Configuration - 

* Database creation - 

* Database initialization - 



4:00 - 

rails generate simple_form:install

 stylesheet - @import "bulma";

rails generate devise:install
- some instructions to do

rails g devise:views

rails g controller home index

guard init livereload
bundle exec guard


some styling for devise layouts

rails g devise User

config -> initializer -> devise.rb
  config.mailer_sender = 'no-reply@collabonit.com'


rails g migration AddNameToUsers name:string    


rails g migration AddTeamIdToUsers team_id:integer   

rails g scaffold Team name:string        

rails g migration AddUserIdToTeams user_id:integer   

rails g scaffold Project name:string description:text

rails g migration AddUserIdToProjects user_id:integer
rails g migration AddTeamIdToProjects team_id:integer


  @user = User
  @user.connection
  @user = User.last   



