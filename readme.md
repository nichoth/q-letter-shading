# quiet letter shading
Sass mixin for css 3d letter shading

## install

    $ bower install q-letter-shading

## example

```sass
@import "bower_components/q-letter-shading/q-letter-shading";

h1 {
    margin-left: 1em;
    margin-top: 1em;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    font: {
        family: "Avenir Next", sans-serif;
        size: 6em;
        weight: 900;
    }
    @include q-letter-shading;
}
```

[demo](https://d9ca95fa4f4d0194863b1d59116d9eecbd3a6865.htmlb.in)
