# \<kwc-product-list\>

A formatted, responsive list of Kano products

 - What is it called?
     - kwc-product-list
 - What is it made out of?
     - `kwc-product-card`
 - What variants are needed?
     - With title
     - Without title
 - How does it scale?
     - Desktop: kwc-product-cards sit side by side in a row, wrapping when necessary
     - Mobile: kwc-product-cards are stacked in a single column
 - What style variables are in use?
     - `--kwc-product-list-bg-color` provides the background color (defaults to white)

## Installation
Clone this repository.
Run `bower i`

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test --skip-plugin junit-reporter
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
