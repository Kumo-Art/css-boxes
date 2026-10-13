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