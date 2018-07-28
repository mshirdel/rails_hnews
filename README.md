# Rails for hnews

This repository is an implementation for [hnews](https://github.com/mshirdel/hnews). This is an api only rails project.

## Getting started
To get the Rails server running locally:
```bash
git clone https://github.com/mshirdel/rails_hnews.git
bundle install
rake db:migrate
rails s
```

## Dependencies
* [Devise](https://github.com/plataformatec/devise) For implementing authentication.
* [Jbuilder](https://github.com/rails/jbuilder) Default JSON rendering gem that ships with Rails, used for making reusable templates for JSON output.
* [JWT](https://github.com/jwt/ruby-jwt) For generating and validating JWTs for authentication

