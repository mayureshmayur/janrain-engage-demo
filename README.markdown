# Janrain Engage Demo

This is a Rails app that demonstrates using [rpx_now](http://github.com/grosser/rpx_now)
to add [Janrain Engage](http://www.janrain.com/products/engage) (formerly RPX) to your Rails app.

Janrain Engage allows your visitors to login to your website with their existing accounts on Facebook,
Google, Twitter, Yahoo!, LinkedIn, Windows Live, MySpace, AOL or other networks and then gather their
profile data and publish their activities from your website to multiple social networks.

## Try it

1. `git clone git@github.com:hatem/janrain-engage-demo.git`
2. `cd janrain-engage-demo`
3. Install required gems: `rake gems:install`
4. Run the migration: `rake db:migrate` 
5. Run the app and try the widget: `script/server`

## Use it

1. Login to janrain.com and create a new application
2. Replace `RPXNow.api_key` in `/config/environment.rb` with the API Key of your new application 
3. In the "Sign-in" section of your Janrain dashboard, you can choose the providers you want to be included in the widget. A wizard will guide you if a provider needs some configuration.
Note: a Facebook application needs "Connect URL" which looks like this: https://janrain-engage-demo.rpxnow.com/