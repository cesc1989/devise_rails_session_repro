# Rails 7.1 Example App with Devise 4.9.3

Repo to try to reproduce "remember me" checked in a Devise 4.9 session with Rails 7.1

## Requirements
- Ruby 3.1.0
- Rails 7.1.1

### Install

```
git clone https://github.com/cesc1989/devise_rails_session_repro
cd devise_rails_session_repro

bundle install
bin/rails db:create
bin/rails db:migrate

bin/rails server -p 5400
```
