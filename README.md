[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

# Tasks API

A lightweight REST-API to handle task manager clients.

##### Running the project locally

Install dependencies
[For Mac's M1 only] Run `bundle config set force_ruby_platform true` before bundle.

```
bundle
```

Initialize the DB

```
rails db:create
```

```
rails db:migrate
```

Run the server

```
rails s
```

Now your port 3000 is running the API 😎
