Ember.SimpleAuth and Rails 4 demo
==================================

This is a demo on how to use Ember.js with [Ember.SimpleAuth](https://github.com/simplabs/ember-simple-auth) plugin and Rails 4 for the backend stuff + assets management.

### Versions used

* Ember.js - 1.4.0
* Ember.SimpleAuth - 0.2.0
* Rails - 4.0.4

### Getting stuff to work

Only a couple of steps:

```
bundle install
rake db:migrate
rake db:seed
```

 You can
login with the following credentials:

```
login: ember
password: password
```

#### Test

The example includes a sample integration test (see `test/javascripts/integration/login_test.js`)

### gems used (additional)
gem "thin"
gem "quiet_assets"

gem 'ember-rails'
gem 'ember-source', '~> 1.4.0'

gem 'qunit-rails'


