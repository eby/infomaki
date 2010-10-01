# Infomaki

Lightweight usability testing webapp inspired by [FiveSecondTest](http://fivesecondtest.com/)

* Background: http://labs.nypl.org/2009/02/16/introducing-infomaki-bite-sized-usability-testing/

## Requirements

* Ruby on Rails

## Installation

1. Have Ruby on Rails 2.2+ running, along with the database of your choice.
2. Check out the Infomaki source code from our Subversion repository or by downloading the .zip file (see the Sourceforge project site for details).
3. Update the config/database.yml file with your local database settings.
4. From the command line, change the directory to the root of the Infomaki application and run “rake db:migrate” to build the database structure.
5. Install the required RubyGems (running “rake gems:install” from command line should do the trick).
6. Start the Rails server (type “script/server”). If all goes well , you should see the project home page at http://0.0.0.0:3000/
7. To create content, go to http://0.0.0.0:3000/initiatives and log in with username “admin@admin.com” and password “rootroot”.

## LICENSE

* GNU General Public License (GPL)