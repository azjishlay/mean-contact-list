# mean-contact-list

A contact list app, based on [this](https://devcenter.heroku.com/articles/mean-apps-restful-api) tutorial, that creates a RESTful API server with Node.js and Express, and then built with AngularJS to consume the API web service. Deploy to Heroku, or use the command line to run the app locally.

```
$ heroku local
```

Before creating a local `.env` file, make sure it will not be updated to source control, as it should only be used for local configuration.
```
$ echo .env >> .gitignore
```

Create a local `.env` file in the project directory, and specify the config vars, as below:
```
MONGODB_URI=mongodb://localhost/<database-name>
```

or, follow the format for a remote connection:
```
MONGODB_URI=mongodb://<username>:<password>@<host-name>
```

If using a local database, don't forget to start MongoDB before running the app.

```
$ mongod
```

## Additional Resources

* [Heroku CLI](https://devcenter.heroku.com/articles/heroku-command-line)
* [Heroku Local](https://devcenter.heroku.com/articles/heroku-local)
* [Heroku Learning](https://devcenter.heroku.com/categories/learning)
