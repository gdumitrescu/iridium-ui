### iridium-ui - frontend development

Sample project using [Iridium](https://github.com/radiumsoftware/iridium) - the toolchain for JavaScript application development and [Testem](https://github.com/airportyh/testem) - the test runner for JavaScript

 - install dependencies

```bash
$ bundle install
```
 - generate app and start development server, available at http://localhost:8080

```bash
$ bundle exec iridium generate app frontend
$ cd frontend && bundle exec iridium server
```

 - test your JavaScript (Jasmine and PhantomJS as defaults)

```bash
$ npm install -g phantomjs testem 
$ testem
```

### Credits

* [Iridium](https://github.com/radiumsoftware/iridium)
* [Testem](https://github.com/airportyh/testem)


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/gdumitrescu/iridium-ui/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

