# \<kwc-auth\>

Front end for Kano&#39;s authentication flow.

 - What is it called?
     - kwc-auth
 - What is it made out of?
     - Describe here the contents of this component
 - What variants are needed?
     - Variant 1:
     - Variant 2:
     - Variant 3:
 - How does it scale?
     - Desktop: ...
     - Mobile: ...
 - What style variables are in use?
     - Style 1: ...
     - Style 2: ...

## Properties
  * assetsPath: Path for assets used during the auth flow.
  * errors: Keeps track of error messages.
  * email: Input value.
  * firstName: Input value.
  * isForceSignup: 
  * newsletter: Flags if user wants to subscribe to newsletter.
  * opened: Flags modal is opened
  * password: Input value.
  * processing: Flags if component is waiting an answer from server or parent component.
  * terms: Flags if user has accepted terms and conditions.
  * username: Input value.
  * worldUrl: Kano world URL.
 
 If `assetsPath` is given the modal will look for a motif icon at `${assetsPath}/avatar/judoka-face.svg` and an arrow icon at `${assetsPath}/icons/link-arrow.svg` so you need to provide those files.

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
