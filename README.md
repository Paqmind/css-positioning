# CSS Positioning

High-level overview of CSS positioning techniques for 2015.

The most important subject. Used everywhere: layouts, menus, forms...

Expensive to redevelop after a wrong choice.

Accepted solutions must be responsive-friendly.

### Negative margin

\- not responsive

### Absolute position

\- no sibling concept

### Fixed position

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

### Negative margin

???

### Absolute position

Terminal elements: popups, banners, icons, logos.

### Fixed position

Sticky elements: headers, footers, menus.

### Tables

Pure text content in table representation.

### Floats

Their primal purpose: wrap text around image.

### Inline Blocks

???

### Flexbox 

Site layout, menus, breadcrumbs, buttons, forms.

## Centering

### Absolute Position + Defined Dimensions

```css
.center {
  position: absolute;
  top: 0; left: 0; bottom: 0; right: 0;
  width: 50%; height: 50%;
  margin: auto;
  overflow: auto; /* scrolls if content is too wide or too high */
  
  /* Resize is also supported */
  resize: both;
  max-width: 100%;
  max-height: 100%;
  
  /* Can be used to center an image */
  /* heigth: auto */
}
```
