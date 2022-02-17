git init
git add .
git commit -m "initial setup"
heroku login
heroku apps:rename pof-teeming
git push heroku master
