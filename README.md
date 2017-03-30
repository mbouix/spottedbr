#README

*PS: This is no longer maintained.*

To setup the server you need to first clone the repo in your local server.

Run ```bundle install``` from the command prompt.

Now go to ```config/database.yml``` file and configure the database which you want to use along with entering the username and password.

Now run

```rake db:migrate```

This will create all the tables for you.

All you have to do now is to start the rails server. You can do that by typing the following command.

```rails s```
