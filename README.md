# grid
css responsive grid

##viewports##
- mobile: smaller 500px
- tablet: bigger 500px
- desktop: bigger 768px

##usage##

css class usage:

###floats###
- fr: float right
- fl: float left
- cf: clear float

###rows###

- r: row

###columns###
nesting possible. column widths change on smaller viewports
- c1: 100%
- c1_2: 50%
- c1_3: 33.33%
- c2_3: 66.66%
- c1_4: 25%
- c3_4: 75%

###example###
```html
<div class="r">
  <div class="c1_2">1_2</div>
  <div class="c1_2">1_2</div>
</div>
<div class="r">
  <div class="c2_3">
    <div class="c1_4">c2_3 c1_4</div>
    <div class="c1_2">c2_3 c1_2</div>
    <div class="c1_4">c2_3 c1_4</div>
  </div>
  <div class="c1_3">c1_3</div>
</div>
```
