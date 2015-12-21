# README

Runs remotely on Heroku with

* `heroku create` 
* heroku redis addon, for example:  `heroku addons:create redistogo:nano`
* `heroku run rake db:migrate`
* Puma server that runs two separate processes using Procfile + middleware that sets up socket connection. 

## Learn More! 

Checkout my blog post on deploying action action cabel to heroku: http://www.thegreatcodeadventure.com/deploying-action-cable-to-heroku/

Checkout Nithin Bekal's excellent app with action cable + web server running on a single process: https://github.com/nithinbekal/actioncable-chat-example
