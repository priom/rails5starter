# Rails 5 Starter Project

[![Build Status](https://semaphoreci.com/api/v1/priom/rails5starter/branches/master/shields_badge.svg)](https://semaphoreci.com/priom/rails5starter)

The only rails 5 starter project you will ever need to start your project right away.

See [demo](https://rails5starter.herokuapp.com/)

* Ruby version: 2.4.1

* Rails version: 5.0.2


**List of all components used**  

* Bootstrap 3
* FontAwesome CDN
* Devise
* Devise Bootstrap Views
* Carrierwave
* Cloudinary
* Mail Form

**Instructions**
1. git clone https://github.com/priom/rails5starter.git
2. cd rails5starter
3. bundle
4. rails db:migrate
5. rails server


**For Sendgrid to work on PRODUCTION**
1. heroku addons:create sendgrid:starter
2. Login to you dashboard, go to your app, then addon and then go to sendgrid.
3. AND MAKE SURE TO ACTIVATE AND CONFIRM YOUR EMAIL. IT'S VERY IMPORTANT FOR YOUR APP'S EMAIL TO WORK.


**For Cloudinary to work on DEVELOPMENT**
1. Create a new account at [cloudinary](http://cloudinary.com/)
2. Look at config/initializers/cloudinary.rb
2. Set config variables in your .zshrc on your computer home director y(not project directory).
4. That's it! Your image uploading should work now.


**For Cloudinary to work on PRODUCTION on HEROKU**
1. heroku addons:create cloudinary:starter
2. heroku config:set CLOUDINARY_CLOUD_NAME="cloudname"
3. heroku config:set CLOUDINARY_API_KEY="apikey"
4. heroku config:set CLOUDINARY_API_SECRET="apisecret"
5. heroku sets up the CLOUDINARY_URL by default.
6. AND also don't put any quotes while setting the config

If you are using Rubymine then open by 'mine .' in your terminal.

Open [localhost](http://localhost:3000) in your browser.
See [live demo](https://rails5starter.herokuapp.com/)

P.S. I'm using free heroku account so, it might a little while for loading it first time.

Open issues if there's any.
