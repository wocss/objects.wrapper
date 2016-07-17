# Wrapper

> Object

The `wocss-objects-wrapper` module contains the wrapper object, its like `container` [bootstrap class](http://getbootstrap.com/css/#overview-container).

Install using npm:

```sh
$ npm install wocss-objects-wrapper --save
```

## Usage

With a tool like [webpack](https://webpack.github.io/) you can import this module writing:

```scss
// dependencies imports

@import '~wocss-tools-layout';
```

Then use `o-wrapper` class for a responsive fixed width container.

```html
<div class="o-wrapper">
  <!-- here your content -->
</div>
```

## Dependencies

* [wocss-settings-defaults](https://github.com/wocss/settings.default)
* [wocss-tools-layout](https://github.com/wocss/tools.layout)
