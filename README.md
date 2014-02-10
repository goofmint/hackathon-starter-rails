Hackathon Starter Rails
=======================

Hackathon starter for Rails developer. Inspired by [hackathon-starter](https://github.com/sahat/hackathon-starter).

# Demo

[http://hackathon-starter-rails.herokuapp.com/](http://hackathon-starter-rails.herokuapp.com/)

# Usage

    $ git clone https://github.com/moongift/hackathon-starter-rails
	$ cd hackathon-starter-rails
	$ mv config/webapi.yml.default config/webapi.yml
	# Edit webapi.yml
	$ bundle install
	$ rails s

# webapi.yml

```
development:
  facebook:
    key: key
    secret: secret
  twitter:
    key: key
    secret: secret
```

## Facebook

Goto [Facebook developers](https://developers.facebook.com/). And create new app.

- URL is **http://localhost:3000/**
- Enable Client OAuth Login
- Enable Embedded browser OAuth Login

## Twitter

Goto [Twitter Developers](https://dev.twitter.com/). And create new app.

Fix key and secret to your app's.

# Features

- [Bootstrap](getbootstrap.com)
- [Font awesome](fortawesome.github.io/Font-Awesome/)
- OAuth Login (Facebook / Twitter) using OmniAuth
- ID/Password Login (Devise)

# LETS'S HACKING!

# LICENSE

MIT License.


