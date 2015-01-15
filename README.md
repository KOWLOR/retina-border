# Retina-border
A SASS mixin to easily add thin borders to your elements.

On a retina device using the classic
```sass
.foo
    border: 1px solid black
```

will render 2 physical pixels.
This mixin creates a fake border, with a svg line in the background of your element.
The render of the line will be 1 physical pixel on a retina screen.

## How to use : 

```sass
.foo
     +retina-border(top $primary-color, bottom #bada55)
```
