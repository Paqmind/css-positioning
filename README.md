# CSS Positioning

High-level overview of CSS positioning techniques for 2015

Most important stuff. Site layout, menus, breadcrumbs, buttons, forms. 

All techniques before Flexbox are fundamentally flawed as general solutions.

### Absolute positioning

\- no sibling concept

### Tables

\- not responsive

\- problems with absolute positioned children

\- problems with intercell spacing

\- problems with cell overflow

### Floats

\- horizontal only

\- no centering along the main axis

\- no alignment along the cross axis

\- can't force items to have equal height

\- require additional clearing step (several techniques exist)

\- can't force items to have equal height

\- HTML order dependent

### Inline Blocks

\- horizontal only

\+ can be centered along the main axis

\- no alignment along the cross axis

\- absorb whitespace as characters (as all inline elements)

\- can't force items to have equal height

\- HTML order dependent

### Flexboxes

\+ horizontal or vertical

\+ can be aligned along the main axis

\+ can be aligned along the cross axis

\+ can force items to have equal height

\+ HTML order independent

### Grid

???

## Recommended Usage

### Absolute positioning

Ending elements (no other element can dependent from their position).

### Tables

Pure text content in table representation.

### Floats

Their primal purpose: wrap text around image.

### Inline Blocks

???

### Flexbox 

Site layout, menus, breadcrumbs, buttons, forms.

