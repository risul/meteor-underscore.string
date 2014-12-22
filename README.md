# Underscore.String for Meteor

The [underscore.string](http://epeli.github.io/underscore.string/) string manipulation library repackaged for Meteor.

## Installing

```bash
    meteor add risul:underscore.string
```

## Usage

Non-conflicting functions are available in `_` directly. All functions,
including conflicting functions, are available in `_s` and `_.str`.

Example:

````javascript
_.str.include('Underscore.string', 'string'); // => true
````

## NOTE

Based off https://github.com/TimHeckel/meteor-underscore-string/ but updated to latest version.
