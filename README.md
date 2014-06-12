ddGrid
=========

**Two SCSS column grid mixins for responsive, non-responsive, or a combination layout by [David Davis].**

  - SCSS mixin for fixed and fluid layouts, for instance you might want to place a fixed pixel div inside of a fluid div


How To?
-----------

* Import the grid before the mixins scss files into your main scss file
* Modify the max-width, column width, gutter width, and breakpoint values inside of _grid.scss
* Apply the clearfix as usual

Then just implement it in your main scss file, for example:

```sh
.someDiv {

	@media screen and (min-width: $desktop) {

            @include fluid-grid-unit(6);
	}
}
```

[David Davis]:http://david-james-davis.com
