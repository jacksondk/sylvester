# Sylvester

Vector and Matrix math for JavaScript. [See the website](http://sylvester.jcoglan.com)
for documentation.


## Development

Sylvester is built using `jake` and tested with JS.Test. Tests should run on all
target platforms, including browsers, Node and other JS runtimes.

Install the build tools (requires Rubygems and npm)

    gem install bundler
    bundle install
    npm install

To build the library from source:

    bundle exec jake

To test, run using various JS binaries and open the tests in the browser:

    node test/console.js
    v8 test/console.js
    rhino test/console.js
    # etc
    
    open test/browser.html

To view the website locally:
    
    staticmatic preview site


## License

(The MIT License)

Copyright (c) 2007-2012 James Coglan

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the 'Software'), to deal in
the Software without restriction, including without limitation the rights to use,
copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the
Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
