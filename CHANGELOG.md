## 3.2.0 / Unreleased
* [BUGFIX] Raise failures from nested contexts [#170]
* [FEATURE] Add `ostruct` dependency to gemspec.
* [FEATURE] Add support for Ruby 3 pattern matching on the Context [#200]

## 3.1.2 / 2019-12-29
* [BUGFIX] Fix Context#fail! on Ruby 2.7

## 3.1.1 / 2018-05-30

* [BUGFIX] Allow Context#fail! to accept a hash with string keys
* [ENHANCEMENT] Many documentation updates

## 3.1.0 / 2014-10-13

* [FEATURE] Add around hooks

## 3.0.1 / 2014-09-09

* [ENHANCEMENT] Add TomDoc code documentation

## 3.0.0 / 2014-09-07

* [FEATURE] Remove "magical" access to the context through the interactor
* [FEATURE] Manage context values via setters/getters rather than hash access
* [FEATURE] Change the primary interactor API method from "perform" to "call"
* [FEATURE] Return the mutated context rather than the interactor instance
* [FEATURE] Replace interactor setup with before and after hooks
* [FEATURE] Abort execution immediately upon interactor failure
* [ENHANCEMENT] Build a suite of realistic integration tests
* [ENHANCEMENT] Move rollback responsibility into the context

## 2.1.1 / 2014-09-30

* [FEATURE] Halt performance if the interactor fails prior
* [ENHANCEMENT] Add support for Ruby 2.1

## 2.1.0 / 2013-09-05

* [FEATURE] Roll back when an interactor within an organizer raises an error
* [BUGFIX] Ensure that context-deferred methods respect string keys
* [FEATURE] Respect context initialization from an indifferent access hash

## 2.0.1 / 2013-08-28

* [BUGFIX] Allow YAML (de)serialization by fixing interactor allocation

## 2.0.0 / 2013-08-19

* [BUGFIX] Fix rollback behavior within nested organizers
* [BUGFIX] Skip rollback for the failed interactor

## 1.0.0 / 2013-08-17

* Initial release!
