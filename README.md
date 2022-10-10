# How to Compile

Go on the terminal project and make the command : composer update

Then create a .env file

Copy the .env.example and paste in the .env 

Go on the terminal project and go to the folder " database " with the command : cd database

Then make the command with the .sql on database : sqlite3 filename.sql < filename.sqlite

Change in your .env : DB_CONNECTION = sqlite 

And copy the path of ur filename.sqlite on your .env : DB_DATABASE = /you/.../filename.sqlite

Then go back to your terminal project and make the command : php artisan key:generate

For the end make the command : php artisan serve 
