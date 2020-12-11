# example-go-webapp

A barebones Go app, which can easily be deployed to Heroku.

## Running Locally

```sh
$ git clone https://github.com/trentrosenbaum/example-go-webapp.git
$ cd example-go-webapp
$ go build -o bin/example-go-webapp -v .

$ heroku local
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

## Deploying to Heroku

```sh
$ heroku create
$ git push heroku main

$ heroku open
```

or

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)
