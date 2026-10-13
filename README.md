# CSS Notes

## What is CSS?
-CSS stands for **Cascading Style Sheets**


## Connecting CSS
- '<link rel="stylesheet" href="styles.css">' goes in the '<head>'.
- One CSS file can style every page that links to it.


## A CSS Rule
-Shape: 'selector { property: value;}'


## Selectors
- 'p' = element selector. Styles every p element
- '#intro' = id selector. Styles one element
- '.card' = class selector. Styles elements in the same class


## div
- '<div.'> = a box with no meaning. Used for grouping and styling.
- If a meaningful tag fit ('<section>', '<header>') use that instead.


## When rules fight
- More specific wins: id<- class<- element.
- If they're tied, the rule lower in file wins.
- '.card p' = any p inside a .card (the space means "inside").


## Text
- 'font-family' = a list of fonts. The browser uses the first one it has.
- 'font-size' = sets how big the text is.
-'font-weight' = sets how thick the text is.
- 'text-align' = left, center, or right.
- 'text-decoration:none' takes the underline off of links
- Text styles on 'body' get passed down to everything inside it

## Box Model
- Every element is a box: content -> padding -> border -> margin.
- Padding = space inside the border. Get the background color.
-Border = the outline.
- Margin = space outside of the border. pushes other boxes away.


## Block vs Inline
- Block ('div', 'p', 'h1', 'section'): starts on a new line, takes the full width.
- Inline ('a', 'strong', 'span'): sits in the line of text. Ignores width and height.


## Flexbox Notes

## dispaly: flex
- 'display: flex' goes on the PARENT.
- The parent becomes a flex container. Its direct children become flex items.
- Only direct children. things inside the children aren't affected.


## The two axies
- Main axis = the direction the items go (horizontal by default)
- Cross axis = the other direction (vertical by default)
- 'justify-content' works on the main axis.
- 'align-items' works on cross axis.


## justify-content and gap
- 'spac-between' = first item at the start, last at the end, and even space between the rest.
- 'gap' = minimum space between flex items





## align-items
- Default is 'stretch'. thats why flex items are all the same height
- 'center' lines up their middles



## flex-direction
- 'row' (default) = main axis goes left to right
-'column' = main axis goes top to bottom.
- Changing direction flips what justify-content and align-items do


## flex-wrap
- Default is 'nowrap'. flex items shrink instead of moving to a new line
- 'flex-wrap: wrap' lets them drop to the next line.