# Responsiveness

## CSS Units

<br/>

### Fixed layout 
`px` - Pixels

### Fluid layout
`%` - Percentage

`auto` - Automatic

`vh` - Viewport Height

`vw` - Viewport Width

#

### Fixed texts
`1px` = 0.75pt
`16px` = 12pt;

### Fluid texts
`em` - Multiplied by parent tag
`rem` - Multiplied by root(html)

## Display Grid tricks

### template columns
`grid-template-columns: repeat(auto-fit, minmax(250px, 1fr))`

## CSS Media queries

```css
    @media (max-width: 320px){
        #form h3{
            font-size: 2rem;
        }
    }
```
## HTML Media queries

```html
    <link rel="stylesheet" href="responsiveness.css" media="screen and (max-width: 890px)" />
    <link rel="stylesheet" href="print.css" media="print" />
```

## Image stylization

```css
    .image {
  width: 100%;
  padding-top: 56.25%; /* 16:9 */

  overflow: hidden;
  position: relative;
}

    .image img {
  width: 100%;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
```