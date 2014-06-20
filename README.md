heroku-jetty-war
================

Example project to deploy a war and execute on heroku with the jetty-runner

Place the war you want to deploy in src/main/resourcs/war and just push to heroku

git push heroku master

This behaves exactly like any other java heroku jetty runner app but provides the flexibility to build your war upfront, 
this can be crucial if you want to use dependencies from on premise maven repositories.
