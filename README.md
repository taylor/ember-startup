## Helper to quickly create a startup Ember app

Create your project and get the rakefile:

    mkdir my-ember-project
    cd my-ember-project
    wget -O rakefile bit.ly/EmberStartup

(The full URL is: https://raw.github.com/jfreeze/ember-startup/master/rakefile)

Then run the setup:

    rake ember:setup

The ember:setup command creates a sinatra project and a basic ember app.
It downloads ember.js and ember-data.js as well as a few other needed javascript libraries.

## Running the App

If you don't have the following gems, install them with

    gem install sinatra sinatra-reloader thin 

Launch the web server with:

    thin start

and browse to http://localhost:3000.

You should see 'Success: You are running Ember!'

###Have fun.

*Note: the rake file is very simple and assumes Linux or Mac shell commands are available to unzip bootstrap.zip and run wget*


## Starting Over

To clear out ALL directories ember:setup created, run

    rake ember:clean

