# keymaster-rails

[Keymaster](https://github.com/madrobby/keymaster), bundled for Rails 3.0 and up.


## Rails 3.1+

For Rails 3.1 and greater, the files will be added to the asset pipeline and available for you to use.

To enable:

* Add the following line to the file `app/assets/javascripts/application.js` (or other [sprockets](https://github.com/sstephenson/sprockets) manifest):

``` javascript
//= require keymaster
```


### Installation

* Add `keymaster-rails` to your Gemfile
* Run `bundle`

Enjoy!


## Rails 3.0

This gem adds a single generator to Rails 3, `keymaster:install`. Running the generator will install the JavaScript file necessary to use Keymaster.

### Installation

* Add `keymaster-rails` to your Gemfile
* Run `bundle`
* Invoke the generator: `rails generate keymaster:install`
* Add the following to your layout or view files:

```erb
<%= javascript_include_tag "keymaster" %>
```

You're done!


## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Added some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request


## License

**keymaster-rails**

* Freely distributable and licensed under the [MIT license](http://phlipper.mit-license.org/2012/license.html).
* Copyright (c) 2012 Phil Cohen (github@phlippers.net) [![endorse](http://api.coderwall.com/phlipper/endorsecount.png)](http://coderwall.com/phlipper)
* http://phlippers.net/

**Keymaster JS**

* Freely distributable and licensed under the MIT-style license.
* Copyright (c) 2011 Thomas Fuchs
* https://github.com/madrobby/keymaster

Copyright (c) 2011 Thomas Fuchs

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.