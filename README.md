# Vagrant Testing Tool/Library

`vagrant-testlib` is both a library and command-line tool for testing
Vagrant plugins, and is also used to test the core components of Vagrant
itself.

The library provides a set of helper methods in addition to
[RSpec](https://github.com/rspec/rspec) matchers and expectations to help
you both unit test and acceptance test Vagrant components. The RSpec
components are built on top of the helper methods so that the test library
can be used with your test framework of choice.