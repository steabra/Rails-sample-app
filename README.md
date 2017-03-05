# Test project for web application

A pretty much straight forward sample web application, 
with functioning login and signup.
Created using Ruby on Rails.


## Getting started

To get started with the app, clone the repo and then install the needed gems:

```
$ bundle install --without production
```

Next, migrate the database:

```
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:

```
$ rails test
```

If the test suite passes, you'll be ready to run the app in a local server:

```
$ rails server
```

HTML files (with embedded Ruby) can be found in app/views.

CSS files (using Sass) can be found in app/assets/stylesheets.