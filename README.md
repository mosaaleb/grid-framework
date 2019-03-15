
# Introduction:
This is a simple 12 columns grid framework. We still believe in the power of CSS, so this is not a alternative for CSS. You will still need to use CSS :grin:. This is a grid ONLY system.


# Setup
sandals.css is hosted on GitCDN, you can easily grab css file. Simply link it inside your html page in `<head>` section.
```html
<link rel="stylesheet" href="https://gitcdn.link/repo/mosaaleb/grid-framework/development/assets/css/sandals.css" />
```
# Usage
## Specs
Everything is a flexbox, it's the main positioning technique in `sandals.css`. So make sure that you fully understand how these classes work `row-g`, `container-g`, `container-fluid-g`, and `col-*-g` 
**Note:** `*` is the number of columns from `1` to `12`

## Box-sizing:
We are using border-box as default box-sizing
```css
html {
  box-sizing: border-box;
}

*,
*:before,
*:after {
  box-sizing: inherit;
}
```


## Grids
We are using 12 columns grid with 10px gutter between every columns.

## Padding & Margins

We use m and p for padding and margin respectively in both a specific direction with the suffix `t`, `r`, `b` and `l`, or in all directions with varying size `1` to `5` each increases the padding or margin only with `10px`.

### Examples:
- `m-2`  -> 20px margins from all directions
- `pl-3` -> 30px padding from left



## Colors
Colors can be used in:
- background-colors `bg-color-[color]`
- colors `color-[color]`
- fixed border width (1px) color `border-[color]` 

Just replace `[color]` with any of these color names;
`white`, `red`, `blue`, `black`, `gray`, `dimgray`, `gold`, `green`, `yellow`, `youngblue`, `purple`, `mango` and `transparent`.

## Font Size
Font sizes are varied from `font-size-1` to `font-size-8` with a span of `.25em` starting from `.5em`. It's not so flexible, but remember you can always use custom css.


## Font Weight
Font weights are varied from `300`, `400`, `500`, `700` and `800` with the classes `fw-light`, `fw-normal`, `fw-medium`, `fw-bold` and `fw-bolder` respectively.


## Flex 
First to use custom flex boxes, you just need to add `flex` class to your tag.


### Flex Direction
You can specify the direction using `dir-horizontal`, `dir-vertical`, `dir-horizontal-reverse` or `dir-vertical-reverse` for the flex parent.

### Flex Horizontal Positioning
You can use `horizontal-start`, `horizontal-end`, `horizontal-center`, `horizontal-around` and `horizontal-between` to adjust the *content* justification horizontally inside the flex parent. 

### Flex Vertical Positioning
Similarly, you can use `vertical-start`, `vertical-end`, `vertical-center`, `vertical-around` and `vertical-between` to adjust the *content* justification vertically inside the flex parent. 


**Okay, but what about positioning items?**
## Flex item Positioning
Also, you can use `vertical-align-start`, `vertical-align-end`, `vertical-align-stretch`, `vertical-align-center`, `vertical-align-baseline` for item positioning.



# Contributers

[Zeha Irawan](https://github.com/JangkarBumi)

[Muhammad Ebeid](https://github.com/mosaaleb)


