tagged: #css #web-dev
# css gradients

> reference: [CSS linear-gradient() function (w3schools.com)](https://www.w3schools.com/csSref/func_linear-gradient.asp) 

## basic syntax
### linear-gradient
```css
element {
  background-image: linear-gradient(_DIRECTION_, _COLOR-1_ _POSITON-1_, _COLOR-2_ _POSITION-2_, _ETC_);
}
```
*-- note that direction, color, and position are just my own arbitrary names for the values --*
- can have arbitrarily many `COLOR` arguments (comma separated)
- `POSITION` is optional - it specifies how far into the gradient this color should start. if not specified, the gradient is just split evenly between each of the colors listed.
- `COLOR` and `POSITION` are separated only by a space
- `DIRECTION` is written either in words like `to bottom left`  or in degrees like `90deg` - note that the word "to" is only required for the former
- it appears that if no direction is given, it defaults to  `to bottom`
- but weirdly, that's not the same as writing  `0deg` ! it looks like `0deg` is equivalent to `to top` instead...
	- `0deg` equals `to top`
	-  `90deg` equals `to right`
	-  `180deg` equals `to bottom`
	-  `270deg` equals `to left`

### repeating-linear-gradient
```css
element {
  background-image: repeating-linear-gradient(_DIRECTION_, _COLOR-1_ _POSITON-1_, _COLOR-2_ _POSITION-2_, _ETC_);
}
```
- all the args are basically the same as regular `linear-gradient` above, but in this case, it only generates a gradient as long as the last `POSITION` given, and then it fills up the rest of the space by tiling the same gradient over again
- **if no positions are given, then it behaves identically to regular `linear-gradient` 
- *tip:* i don't think it includes an option for making the direction alternate, so i'm guessing that if you want this to look decent, you should make sure your list of colors ends by fading back into the same color that it started with.

## examples
[Tryit Editor w3schools: repeating linear gradient](https://www.w3schools.com/css/tryit.asp?filename=trycss3_gradient-linear_repeating)

> to make a hard edge between two colors (aka solid stripes!), list the same position for both colors

```css
#grad5 {
  background-image: repeating-linear-gradient(45deg, red 0px, red 10px, yellow 10px, yellow 20px);
}
```