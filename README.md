Bootstrap3Grid
==============

Upgrade Bootstrap 2.x to Bootstrap 3.x Grid System Only

If you want to use the more powerful Bootstrap3 scaffolding grid on your existing Bootstrap2 project, 
just add this CSS file.  The older grid design is still supported, but you can now use the new .col-* instead
of .span* in your columns.

A big difference between version 2 and 3 is the box-sizing CSS property.  In bootstrap 3, box-sizing is set to
border-box for all elements, like so:

*,
*:before,
*:after {
  -webkit-box-sizing: border-box;
     -moz-box-sizing: border-box;
          box-sizing: border-box;
}


With border-box property set, width and height (and min/max properties) on the element determines the border 
box of the element. That is, any padding or border specified on the element is laid out and drawn inside this 
specified width and height. The content width and height are calculated by subtracting the border and padding 
widths of the respective sides from the specified 'width' and 'height' properties.

This CSS file contains the minimum required properties and media queries to make use of 3.x responsive grid.
