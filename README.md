# Material Web Components

This is a package that bundles all of the web components from the [Material Web repo](https://github.com/material-components/material-web) so that you don't need a module bundler to use them.

Components:

- `button`,
- `checkbox`,
- `circular-progress`,
- `circular-progress-four-colors`,
- `dialog`,
- `drawer`,
- `fab`,
- `formfield`,
- `icon-button-toggle`,
- `icon-button`,
- `icon`,
- `linear-progress`,
- `list`,
- `menu`,
- `radio`,
- `select`,
- `slider`,
- `snackbar`,
- `switch`,
- `tab-bar`,
- `tab`,
- `textarea`,
- `textfield`,
- `top-app-bar-fixed`,
- `top-app-bar`,

Variants:

- `component.js` The unminified, bundled component in an IIFE format.
- `component.min.js` **RECOMMENDED** The minified, bundled component in an IIFE format.
- `component.esm.js` The unminified component as an ESM module. All imports are reexported.
- `component.esm.min.js` The minified component as an ESM module. All imports are reexported.

All components have `.map` files.

There is also a file that includes all components. This is preferred over manually importing every component since helper libraries (like `lit`) aren't imported multiple times.

To use:

```html
(index.html)
<html>
  <head></head>
  <body>
    <script
      async
      src="https://unpkg.com/material-custom-elements/(component).min.js"
    ></script>
  </body>
</html>
```

As a module:

```html
(index.html)
<html>
  <head></head>
  <body>
    <script
      type="module"
      src="https://unpkg.com/material-custom-elements/(component).esm.min.js"
    ></script>
  </body>
</html>
```

Importing all components:

```html
(index.html)
<html>
  <head></head>
  <body>
    <script
      async
      src="https://unpkg.com/material-custom-elements/all.min.js"
    ></script>
  </body>
</html>
```

As a module:

```html
(index.html)
<html>
  <head></head>
  <body>
    <script
      type="module"
      src="https://unpkg.com/material-custom-elements/all.esm.min.js"
    ></script>
  </body>
</html>
```
