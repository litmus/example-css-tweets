# Litmus Example – Tweets in CSS

## Deploy A Copy
You can easily deploy this application to [Heroku](https://heroku.com) using 
the button below. After creating your [Twitter application](https://apps.twitter.com), 
click the "Deploy to Heroku" button and follow the steps on the next screen to create 
your own version of this application.

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

## Local Development

### Requirements
* Git
* Ruby
* Bundler

### Setup
1. Clone This Repo: `git clone https://github.com/litmus/example-css-tweets.git`
2. Install Dependencies: `cd example-css-tweets && bundle install`
3. Create Environment File: `cp .env.example .env` 
4. Create Twitter Application: https://apps.twitter.com/
5. Enter Your Application's API Credentials in `.env`
5. Run `bundle exec foreman start`
6. Visit [http://localhost:5000/tweets.css](http://localhost:5000/tweets.css)
