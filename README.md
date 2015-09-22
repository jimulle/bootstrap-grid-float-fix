# bootstrap-grid-float-fix
Simple fix for floated grid elements of varying sizes (using inline-block)

Changes the grid elements to inline-block which allows us to alleviate the annoying float issues when elements flow over to a new row.

<table>
<tbody>
<tr>
<td>go from this:</td>
<td>to this:</td>
</tr>
<tr>
<td><img src="http://s4.postimg.org/el7qfdonh/Screen_Shot_2015_09_22_at_12_14_07_AM.png" style="with: 100%;"/></td>
<td><img src="http://s4.postimg.org/r14g94hzh/Screen_Shot_2015_09_22_at_12_13_28_AM.png" style="with: 100%;"/></td>
</tr>
</tbody>
</table>

<br/><br/>

<b>CSS Usage:</b><br/>
Simply add the CSS to your page's main CSS file (or add the CSS file iself as a link).

<b>SASS Usage:</b><br/>
Add `@import "col-fix";` to your bootstrap.scss file

<b>HTML Setup:</b><br/>
Add the class `col-fix` to all elements within the row that needs fixed<br/>
example: 
```
<div class="row">
  <div class="col-sm-12 col-md-6 col-lg-4 col-fix">...</div>
  <div class="col-sm-12 col-md-6 col-lg-4 col-fix">...</div>
  <div class="col-sm-12 col-md-6 col-lg-4 col-fix">...</div>
  ...
</div>
```
