# \<auburn-address-input\>

Form Input for addresses within Auburn city.

## Install

`bower install auburn-address-input`

## View

`cd auburn-address-input`
`bower install`

On modern browsers you can view the demo by serving the /demo/index.html page. For older browsers you'll need to load it into a Polymer (Hybrid/2.0) project and build it with polymer-build (@next)

## Tests

//TODO - Testing Not Implemented!!!

## Known Bugs

1. Using the component with no configuration "basic demo" only works if it's the only auburn-address-input on the webpage. Appears to be a render bug (tested in Chrome 56).
2. Datalist are not supported in Safari
3. Browsers do not show complete datalist. Therefore the browser may be filtering out some of the options.

# Polymer Projects

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create a `build/` folder with `bundled/` and `unbundled/` sub-folders
containing a bundled (Vulcanized) and unbundled builds, both run through HTML,
CSS, and JS optimizers.

You can serve the built versions by giving `polymer serve` a folder to serve
from:

```
$ polymer serve build/bundled
```

## Running Tests

```
$ polymer test
```

Tests have not been completed!!!
Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
