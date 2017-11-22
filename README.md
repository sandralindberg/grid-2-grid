# grid-2-grid
Progressive enhanced grid, from inline-block to flexbox to css-grid. Not very well tested but it probably works in latest browsers and maybe IE9 - IE11. Make sure you do extensive testing before implementing in real project. 

## Classes
__Container__ gets `max-width` based on Breakpoints, remove media-queries for full-width layout (or create a `container--full` class). 

__Row__ can be extended with `row--col-span` to remove column gap in row ANR/OR `row--row-span`to remove row gap in row.

__Col__ created based on Breakpoints.

## Settings:
* __Inline-block__, true/false, to enable/disable the inline-block version of the grid
* __Flexbox__, true/false, to enable/disable the flexbox version of the grid
* __CSS-grid__, true/false, to enable/disable the css-grid version of the grid
* __Columns__, number, number of columns
* __Col-gap__, column gap, e.g. 20px
* __Row-gap__, row gap, e.g. 20px

## Breakpoints
You can add/change/remove breakpoints, but grid is mobile-first so all breakpoints will be used with `media (min-width...)`

## Container-max-width
You can add/change/remove max-widths, but key name needs to be identical to thoose used in Breakpoints. 

## License
MIT © [Sandra Lindberg](https://github.com/sandralindberg)
