# CSS basic syntax

## Including Style:
- Inline
`<h1 style="color: red">`

### Style tag

```html
 <style>
	h1 {
	color : red;
}
</style>
```

### External Stylesheet
- Writing CSS in a separate document & linking it with HTML file

## Color property
- Used to set the color of foreground
- color:  red;
- color:  pink;
- color:  blue;
- color:  green;

### Background Color Property
- Used to set the color of background
- background-color:  red;
- background-color:  pink;
- background- color:  blue;
- background- color:  green;

## Color Systems:
### RGB
- color: (red) rgb(255, 0, 0);
- color: (green) rgb(0, 255, 0)

### Hex (Hexadecimal)
- color : #ff0000;
- color : # 00ff00;

## Selectors
### Universal Selector
- `* { }`
### Element Selector
- `h1 { }`
### Id Selector
- #myId { }
### Class Selector
- .myClass { }

## Text Properties
### text-align
- text-align : left / right / center

### text-decoration
- text-decoration : underline / overline / line-through

### font-weight
- font-weight : normal / bold / bolder / lighter
- font-weight : 100-900
- bold = 400

### font-family
- font-family : arial 
- font-family : arial, roboto

## Absolute Units in css
- pixels (px)
- 96px = 1 inch
- font-size: 2px;

### line-height
- line-height : 2px
- line-height : 3
- line-height : normal

### text-transform
- text-tranform : uppercase / lowercase / capitalize / none
