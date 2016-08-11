# ▲GRID.css

▲ (triangle) grid is a very small flexbox-based responsive grid framework 
- Supports all modern browsers natively
- Supports IE9+ with *respond* & *modernizr* as small dependencies

# Syntax

- *.tri*: The basic grid row, constrained to a user defined width.
  - *.full*: Combined with *.tri*, turns it into a full-width row.
  - *.space*: Combined with *.tri*, adds spacing to each of the child cell/column elements.
- *.angle*: An auto-spaced flexbox cell/column. *!!* DOES NOT WORK IN IE9 *!!*
- *.ang*: Used to begin a determined width cell/column.
  - *.le-(1 to 24)*, *.le-(quarter, third, half, full)*: The percentage based cell/column widths, based on a 24 section grid.
