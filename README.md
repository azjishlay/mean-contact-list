# mean-contact-list

A contact list example app, created with [this](https://devcenter.heroku.com/articles/mean-apps-restful-api) tutorial, and converted to run locally.

Before creating a local `.env` file, make sure it will not be updated to source control, as it should only be used for local configuration.

```
echo .env >> .gitignore
```

Create a local `.env` file in the project directory, and specify the config vars.

```
MONGODB_URI=mongodb://localhost/<database-name>
```

or, for remote connections,

```
MONGODB_URI=mongodb://<username>:<password>@<host-name>
```
