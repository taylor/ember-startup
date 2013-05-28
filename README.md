## Helper to quickly create a startup ember app

Use this rakefile

    mkdir my-ember-project
    cd my-ember-project
    rake ember:setup

The ember:setup command create a sinatra project and a basic ember app.
It downloads ember.js and ember-data.js as well as a few other needed javascript libraries.

## Running the App

If you don't have the following gems, install them with

    gem install sinatra sinatra-reloader thin 

Run the app with:

    thin start

###Have fun.

*Note: the rake file is very simple and assumes linux or mac shell commands are available to unzip bootstrap.zip*

