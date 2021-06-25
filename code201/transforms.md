# CSS Transforms, Transitions, and Animations

## CSS Transforms
CSS transforms can be either 2d or 3d. Currently browser support for transforms isn't great but it's getting better. To help with this it's good to include the vendor prefixes to the CSS such as in the following:

```div {
  -webkit-transform: scale(1.5);
     -moz-transform: scale(1.5);
       -o-transform: scale(1.5);
          transform: scale(1.5);
}
```
Some CSS transform properties are:

* Rotate, ex: `transform: rotate(20deg)`
* Scale, ex: `transform: scale(.75)`
* Translate, ex: `transform: translate(-10px, 25%)`
* Skew, ex: `transform: skew(5deg, -20deg)`
