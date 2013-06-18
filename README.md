If not yet installed, install RVM

    \curl -L https://get.rvm.io | bash

Clone this project and go to it

    git clone git://github.com/relaxdiego/sso-sample.git
    cd sso-sample

Install the needed gems

    bundle install

Copy settings.yml.example

    cp settings.yml.example settings.yml

Use your favorite text editor to edit settings.yml. Make sure

* mcloud_url has the http:// or https:// prefix
* credentials for sample_user are valid

Start the server

    ./start
