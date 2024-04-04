# Pester

## Mocks

There can be times when you want to test something but not actually run it.

For example, if you have a function that builds a server, you don't actually want to build it to test your code.

This is where mocking comes into play!

We'll look at an example where we need to test calling an API.
We want to make a POST to the API but we don't want to actually hit our API!
We just want to mock how it would behave.

This is generally considered a _Unit Test_. 
An _Integration Test_ is a test where you actually would interact with a live system.
