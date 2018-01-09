# Ruby on Rails Tutorial sample application

This is the sample application for 
[*Ruby on Rails Tutorial:
Learn Web Development with Rails*](http://www.railstutorial.org/)
by [Michael Hartl](http://www.michaelhartl.com/)

And database using 
[*MongoDB*]
(https://docs.mongodb.com/mongoid/master/tutorials/mongoid-installation/) 

## License

All source code in ther [Ruby on Rails Tutorial](http://railstutorial.org/) is available jointly under the MIT License and the Beerware License.  See [LICENSE.md](LICENSE.md) for details

## Getting started

To get started with the app, clone the repo and then install the needed gems :
...
$ bundle install
...

Next, config the database:
...
$ rails mongoid:config
...


Finally, run the test suite to verify that everything is working correctly:
...
$ rails test
...

If the test suite passes, you'll be ready to run the app in a local server:
...
$ rails server
...

For more information, see the
[*Ruby on Rails Tutorial* book](http://www.railstutorial.org/book)