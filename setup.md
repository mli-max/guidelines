# Suggested application setup

**bold** is for the best option

### Ruby verison
* 1.8 (only if legacy and/or if you must)
* 1.9
* 2.0
* **2.1**

### Rails version
* 2.x (only legacy and/or if you must)
* 3.0 (only legacy, as this version is still without assets pipeline)
* 3.x where x >= 1
* **4.x**
* ALWAYS go for assets pipeline (and [Rails Assets](https://rails-assets.org/))

### Databases
* **redis** - best for cache, queue
* **posgres**
* mysql - only if postgres is not an option
* mongodb - handle with CARE, as it always get messy in production
* memcached
* neo4j - graph base

### External APIs
* **json**, **rest** - for the win
* xml, soap - not very cool, but managable

### Full-text search engines
* **elasticsearch** - best from -v 1, as they introduced Marvel for ES&query checking
* **solr**
* lucene

### Javascript
* **AngularJs** - [We are angular developers](http://codetunes.com/2013/we-re-angularjs-developers/)
* **coffeescript**
* Backbone - please use angular instead
* Ember - please use angular instead
* Jquery - if can, please use angular instead
* Nodejs


### Frontend (css/html)
* bootstrap
* **sass**
* bourbon, compass
* **BEM convention**
* haml
* **slim**

### Websockets
* websockets
* eventmachine
* node.js
* **faye**
* pusher
* **pubnub**

### Mobile
* phonegap
* sencha / titanium

### Single page applications
* **SPA** vs ajax vs plain old

### Error tracking
* airbrake
* **sentry**

### Protocols
* ftp, sftp, **ssh**
* http vs https
* SSL certificates

### SCM
* **git** (**github**, bitbucket)

### Monitoring
* datadog
* librato
* **newrelic**

### Analytics

* google analytics
* kissmetrics / mixpanel

### Cron / scheduling / background processing
* **sidekiq**
* resque
* delayed_job
* whenever
* clockwork

### i18n
* localeapp

### Mailing
* postmark
* sendgrid
* mailchimp

### Hostings
* heroku ( :( )
* **hetzner**
* rackspace
* amazon AWS (S3 + EC2 + cloudfront)
* self-hosted
  * ubuntu etc.

### Online payments
* one shot vs recurring
  * stripe
  * **braintree**
  * chargify
  * recurly


### Admin panel
* active admin
