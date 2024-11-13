# [Live Preview](https://neqbal.github.io/LandingPage/)

### Flex-Box

The flexible box layout module (usually referred to as flexbox) is a one-dimensional layout model for distributing space between items and includes numerous alignment capabilities.

When working with flexbox you need to think in terms of two axes — the main axis and the cross axis. The main axis is defined by the flex-direction property, and the cross axis runs perpendicular to it.


The main axis is defined by flex-direction, which has four possible values:

1. row - Main axis runs along row
2. row-reverse - 
3. column - Main axis runs along column
4. column-reverse

The cross axis runs perpendicular to the main axis. Therefore, if your flex-direction (main axis) is set to row or row-reverse the cross axis runs down the column

An item with display: flex is called flex container and items inside it are flex items


### Flex grow, shrink and basis 

This property defines how each flex item will grow with respect to others

flex: 1 (shorthand for flex-grow: 1, flex-shrink: 1 and flex-basis: 1)

If each flex item had flex : 1 then they all will grow and shrink the same amount 

If one of the items has flex: 2 then that item will grow and shrink 2 times more. 

Flex basis sets the initial size. So any growing and shrinking will start from basis size.\
Auto in basis tells them to check for any width and height declaration


### Aligning items 

justify-content - aligns items horizontally \
for example justify-content: center will bring the items in center. Similarly there are many more options in justify-content such as end, start. 

align-items - aligns items vertically. \
It also has the same options as justify-content


### Padding, borderm margin

Padding - increases the space between border of the box and content of the box

Border - adds space between margin and padding.

Margin - Increases space between border and adjacent borders of other boxes
