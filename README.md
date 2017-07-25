# \<mtz-permission-check\>

<!-- 
```
<custom-element-demo>
  <template>
    <link rel="import" href="../paper-checkbox/paper-checkbox.html">
    <link rel="import" href="mtz-permission-check.html">

    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<h4>Control User's Authentication status</h4>
<div class="userStatus">
  <paper-checkbox checked="{{signedIn}}">
    Signed In
  </paper-checkbox>
  <paper-checkbox checked="{{anonymous}}">
    Anonymous
  </paper-checkbox>
  <paper-checkbox checked="{{authenticated}}">
    Authenticated
  </paper-checkbox>
</div>
<mtz-permission-check
  anonymous="[[anonymous]]"
  signed-in="[[signedIn]]"
  authenticated="[[authenticated]]"
  restamp>
  <template>
    Top Secret Content
  </template>
</mtz-permission-check>
```

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
