# _grid.scss

Lightweight, customizable CSS grid in Sass. As seen on [thegreatsunra.com](http://thegreatsunra.com).

Supports nested grid sections, pushing and pulling, and appending or prepending.

## Usage

Include [Compass](http://compass-style.org/) and `_grid.scss` in your styles if you wish to customize column widths, gutter widths, or the number of columns.

Include `_grid.css` in your styles if you wish simply to use it out-of-the-box.

  ``` scss
  @import "compass";
  @import "_grid.scss";
  ...
  ```

  ``` html
  <div class="container">
    <div class="span-8">
      <div class="span-2">span-2</div>
      <div class="span-6 last">span-6</div>
      <div class="span-4">span-4</div>
      <div class="span-4 last">span-4</div>
    </div>
    <div class="span-4 last">span-4</div>
      <div class="span-2">span-2</div>
      <div class="span-2 last">span-2</div>
      <div class="span-3">span-3</div>
      <div class="span-1 last">span-1</div>
    </div>
    <div class="span-6">span-6</div>
    <div class="span-6 last">span-6</div>
    <div class="span-12"></div>
  </div>
  ```
