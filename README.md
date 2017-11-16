# \<polymer_01\>

Learn polymer 2.0
[Tutorial](https://www.polymer-project.org/2.0/start/install-2-0)

## 1. Setup
```bash
$  npm install -g polymer-cli

$  mkdir polymer_01
$  cd polymer_01/

$  polymer init
$  polymer serve

```

## 2. Polymer documentation:
### Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

### Viewing Your Application

```
$ polymer serve
```

### Building Your Application

```
$ polymer build
```

This will create builds of your application in the `build/` directory, optimized to be served in production. You can then serve the built versions by giving `polymer serve` a folder to serve from:

```
$ polymer serve build/default
```

### Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
