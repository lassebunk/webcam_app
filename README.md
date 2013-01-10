About
-----

This is a demo on how to get your webcam working with [Rails 3](http://rubyonrails.org).

See my [blog post](http://lassebunk.dk/2011/02/19/paperclip-jpegcam-webcam-rails3/) about this.

Use as you wish but please [drop me a note](http://lassebunk.dk/contact/) if you find it useful and use it on your site – I'd like to hear about that.


Usage
-----

```bash
$ git clone https://github.com/lassebunk/webcam_app.git # copy this repository
$ cd webcam_app
$ bundle install # to make sure you have the Paperclip gem and correct version of Rails
$ bundle exec rake db:migrate # create the database tables
$ script/rails server # run the development web server
```

Then go to [http://localhost:3000/photos](http://localhost:3000/photos).

Copyright © 2013 [Lasse Bunk](http://lassebunk.dk), released under the MIT license