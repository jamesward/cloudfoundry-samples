Deploy on Heroku
----------------

1. Initialize a git repo

        git init

2. Add files to git repo

        git add .

3. Commit the files to the git repo

        git commit -m init

4. Create an app on Heroku

        heroku create -s cedar

5. Add the MongoHQ Add-on

        heroku addons:add mongohq

6. Deploy the app

        git push heroku master

