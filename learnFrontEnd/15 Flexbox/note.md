CSS Flexbox?

display: flex | inline-flex 
    * flex: create a block-level flex container.
    * inline-flex: Creates an inline-level felx container.

flex-direction: row | column | row-reverse | column-reverse 
    Defines the direction of the main axis (how items are placed): 
        * row: left to right (default)
        * column: Top to bottom.
        * row - reverse: Right to left
        * column -reverse ; bottom to top. 

flex-basis: <length> 
    Set the initial size of a flex item before free space is distributed. 
        * Values: auto, content, or specific sizes

justify-content: flex-start | flex-end | center | space-between | space-around
    Align items along the main axis:
        * flex-start: Items packed at the start(default)
        * flex-end: Items packed at the end 
        * center: Items centered 
        * space-between: Equal space betwwen items (no end gaps), 
        * space-around: Equal space around items ( half - gaps at ends).
        * space-evenly: Equal space between and around items. 

align-content: flex-start | flex-end | center | space-between | space-around
    Aligns multiple lines of  items along the cross-axis ( requies flex-wrap: wrap):
        * flex-start: lines packed at the start 
        * flex-end: lines packed at the end
        * center: Lines centered 
        * space-between: Equal space betwwen lines. 
        * space-around: Equal space around lines.
        * stretch: Lines stretch to fill container (default).

align-self: flex-start | flex-end | center | stretch
    Overrides a single item's alignment along the cross-axis:
        * Flex-start: Align to cross-start.
        * Flex-end: Aligns to cross-end.
        * Center: Centers along cross-axis.
        * Stretch: Fills the containers (defaults)
        * Baseline: Aligns to text baseline

flex-grow: <number>
    Defines how much an item can grow to fill extra space.
        * Value: Unitless number (e.g., 2 = twice the growth of others)
        * Default: 0 (no growth)

flex-shrink: <number>
    Defines how much an item can shrink if space is insufficient.
        * Value: Unitless number(e.g, 2 = shrinks twice as much as others)
        * Default 1.

flex-wrap: nowrap | wrap | wrap-reverse
    Controls whether items wrap onto multiple lines:
        *nowrap: Single line default.
        * wrap: multiple lines (top to bottom)
        *wrap-reverse: Muiltiple lines (bottom to top).


flex: <'flex-grow'> <'flex-shrink'> <'flex-basis'> | auto | initial | inherit
    Shorthand for flex-grow, flex-Shrinks, and flex basis:
        *flex: 1 0 200px = Grow: 1, Shrink: 0, Basis: 200px. 
        *auto = 1 1 auto.
        *initial = 0 1 auto
        *none = 0 0 auto

flex-flow: <'flex-direction'> <'flex-wrap'> 
    Shorthand for flex-direction and flex-wrap:
        *Example: flex-flow: row wrap. 


order: <number>
    controls the visual order of items( does not affect source order):
        * Value: interger(e.g, -1, 0, 1). Lower numbers appear first.
        * Default: 0.

link tham khảo: https://codepen.io/enxaneta/full/adLPwv/ 
    https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/CSS_layout/Flexbox
