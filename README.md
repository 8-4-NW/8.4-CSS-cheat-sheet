# 8.4-css-class-doc

This document will serve as our collective repo for css tips and tricks that we discover during our Pursuit Core journey
## Quick links
[Display](#Display)
[Grid](#Grid)
[Flex](#Flex)
[Images](#Images)
[Colors](#Colors)
 
## How does this work?
Anyone can make edit's or PR's to this document.  
<br> 
If you happen to find a CSS rule you are a fan of consider adding it to this document.  
<br>
All Rules should be placed under a broader category. 
<br>
Don't see a category for your rule?  Create a new one with the following syntax :

```md 
## myCategory
```
then add a link in the Quick Links section using the folliwing syntax :
```md
[myCategory](#myCategory)
```



## Display
<--- add display rules here ----- >

## Grid
### Grid-template-areas - alternative way to style parent container for grid:

```css
.parent {
   grid-template-areas: 
    "one one two two"
    "one one two two"
    "three three four four"
    "three three four four";
 }
 .one {
  grid-area: one
 }
```
## Flex 

### display: Flex
This defines a flex container; inline or block depending on the given value. It enables a flex context for all its direct children.

```css
display:flex
```

### flex-direction
This establishes the main-axis, thus defining the direction flex items are placed in the flex container.

```css
flex-direction: row 
```

### justify-content
This defines the alignment along the main axis. It helps distribute extra free space leftover when either all the flex items on a line are inflexible, or are flexible but have reached their maximum size
```css
  justify-conten: flex-start
```
### align-content
This aligns a flex container’s lines within when there is extra space in the cross-axis, similar to how justify-content aligns individual items within the main-axis.
```css
 align-content:space-around;
```

### align-items
This defines the default behavior for how flex items are laid out along the cross axis on the current line. Think of it as the justify-content version for the cross-axis (perpendicular to the main-axis).

```css
   align-items:baseline
```

<------ add flex rules here ----->

## Images 
<------ add image rules here -----> 

## Colors

<------- add Color rules here ----> 
