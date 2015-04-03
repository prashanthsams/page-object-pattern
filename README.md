[ ![Codeship Status for wearehanno/riggings](https://codeship.io/projects/1f2de390-9a4b-0132-45aa-5e3821e41288/status?branch=master)](https://codeship.com/projects/63879)
[![Build Status](https://travis-ci.org/prashanthsams/page-object-pattern.svg?branch=master)](https://travis-ci.org/prashanthsams/page-object-pattern)

# page-object-pattern
Selenium Ruby | Rspec via Page Objects

**To run Selenium tests, Follow the cmd in Terminal**:

 ```
 rspec --format html --out report.html Google_spec.rb
 ```

> RSpec JUnit Formatter

Install the gem:

 ```
 gem install rspec_junit_formatter
 ```

 ```
 rspec --format RspecJunitFormatter  --out rspec.xml Google_spec.rb
 ```

> Fuubar

Install the gem:

 ```
gem install fuubar
 ```

 ```
 rspec --format Fuubar --color Google_spec.rb
 ```

**To run as test suite, Follow the cmd in Terminal**

 ```
 rspec spec/ -t suite
 rspec spec_helper.rb
 bundle exec rake spec
 ```

**To run Rake test, Follow the cmd in Terminal**

 ```
 bundle exec rake spec
 ```
