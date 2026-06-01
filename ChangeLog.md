### 1.2.1 / 2026-05-31

* Formally support Rails 7.1 (widen the activerecord dependency cap to `< 7.2`).
* Add an Appraisal entry and CI gemfile for Rails 7.1.

### 1.2.0

* Add support for Rails 7.0.

### 1.1.0 / 2020-12-24

* Formally support Rails up to 6.1.
* No longer formally support Rails 5.0.x and earlier.
* Drops support for `ruby_protobuf` library.
* Drops support for Ruby < 2.4.

### 1.0.2 / 2017-11-01

* Declare support for Rails 5.1.

### 1.0.1 / 2016-05-15

* Declare support for Rails 5.
* Upgrade development gems, reducing the deprecation warning spam.

### 1.0.0 / 2016-05-15

* Don't allow coder's dump method to fail. Instead, return nil.
* Pass options through correctly, so coder can respect defaults.

### 0.2.3 / 2015-11-21

Update gemspec, gem supports Rails 4.2

### 0.2.1 / 2014-05-20

Tweak detection of field types so booleans are detected.

### 0.2.0 / 2014-05-20

Fix Railtie, so it doesn't error.

### 0.1.0 / 2014-05-19

Initial release: stuff works.
