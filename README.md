# sinking-feeling
Group project primary repository


# Getting MEAN.JS running
There are a whole bunch of prerequisities for getting this running.

## Windows
I followed [some random instructions](https://programmaticponderings.wordpress.com/2014/03/08/installing-and-configuring-mean-stack-and-yeoman-on-windows/) for getting things up and running on windows.

The important parts...

1. Install [Ruby](http://rubyinstaller.org/downloads/), during the install select the option to add it to the PATH.
2. Install [RubyGems](https://rubygems.org/pages/download)
    1. Unzip that download, go to that directory
    2. Run `ruby setup.rb`
    3. Run `gem update --system`
    4. Run `gem update`
    5. Run `gme install sass`
3. Install [MongoDB](https://www.mongodb.com/download-center)
    1. Make a directory (C:\data by default) for the DB
    2. Run `mongod` to start the server (if it isn't in your PATH, you may have to use the full path to it)
4. Install [Node.js](http://nodejs.org/download/)
5. Install node dependencies `npm install -g bower grunt-cli gulp`

## Linux (Ubuntu 14.04)
TBD

# Starting the app

1. Go to the git repository root
2. Run `npm install`
3. Run `MONGO_SEED=true grunt`, seeding it will generate a user named 'user'
   and an admin named 'admin'. Only run this the first time, any future runs, 
   just run `grunt`. 
4. Open your browser and go to [http://localhost:3000](http://localhost:3000)


