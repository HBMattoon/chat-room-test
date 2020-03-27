# WebApp-Template

requirements:
  heroku
  nodemon
  npm

an extremely basic template for a react webapp (WIP)

scripts:
  start -> bundles jsx files and starts server
  start:dev -> starts server using nodemon
  build -> bundles jsx files
  build:dev -> bundles jsx files and watches for any changes

to deploy to heroku
$ heroku login
$ heroku git:clone -a whatever-your-calling-your-heroku-app
$ git push heroku master

note: might need heroku config:set NPM_CONFIG_PRODUCTION=false if dev dependencies not installing;


