# ▲GRID.css

▲ (triangle) grid is a very small flexbox-based responsive grid framework 
- Supports all modern browsers natively
- Supports IE9+ with **respond** & **modernizr** as small dependencies

Like what I do? [Donate me a beer!](https://www.paypal.me/jamesparkninja/4)

### Syntax

- **.tri**: The basic grid row, constrained to a user defined width.
  - **.full**: Combined with **.tri**, turns it into a full-width row.
  - **.space**: Combined with **.tri**, adds spacing to each of the child cell/column elements.
- **.angle**: An auto-spaced flexbox cell/column. **!!** DOES NOT WORK IN IE9, USE THE BELOW FOR THIS INSTEAD **!!**
- **.ang**: Used to begin a determined width cell/column.
  - **.le-(1 to 24)**, **.le-(quarter, third, half, full)**: The percentage based cell/column widths, based on a 24 section grid.
  
### Fallback & Dependencies

For < IE9, we either require some polyfills and dependencies from the following:

* [Modernizr](https://modernizr.com/)
* [Respond](https://github.com/scottjehl/Respond)

Or can use the **triangle-fallback.css** wrapped in a <!--[if lte IE 9]><![endif]--> comment.

(Thanks all!)
