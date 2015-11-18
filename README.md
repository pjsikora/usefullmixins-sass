# Useful Mixins

By: fedojo.com

## List of mixins

<table>
<tr>
	<th>Name</th>
	<th>Description</th>
</tr>
<tr>
	<td>linearGradientFromTop($startColor, $endColor)</td>
	<td>Vertical gradient from top. Remember that for IE you need to append full HEX (#000000 not #000)</td>
</tr>
<tr>
	<td>linearGradientFromLeft($startColor, $endColor)</td>
	<td>Horizontal gradient from left</td>
</tr>
<tr>
	<td>animateAll($time)</td>
	<td>Animate all properties</td>
</tr>
<tr>
	<td>clearfix</td>
	<td>Just a simple clearfix</td>
</tr>
<tr>
	<td>opacity</td>
	<td>IE8 opacity fallback</td>
</tr>
</table>

Primitives
<table>
<tr>
	<th>Name</th>
	<th>Description</th>
</tr>
<tr>
	<td>=rectangle($width, $height, $color)</td>
	<td>Draw rectangle with $width, $height, $color</td>
</tr>
<tr>
	<td>=square($width, $color)</td>
	<td>Draw square with $width and $color</td>
</tr>
<tr>
	<td>=circle($size, $color)</td>
	<td>Draw circle</td>
</tr>
<tr>
	<td>=triangleRight($width, $height, $color)</td>
	<td>Draw triangle directed to right</td>
</tr>
<tr>
	<td>=triangleLeft($width, $height, $color)</td>
	<td>Draw triangle directed to left</td>
</tr>
<tr>
	<td>=triangleTop($width, $height, $color)</td>
	<td>Draw triangle directed to top</td>
</tr>
<tr>
	<td>=triangleBottom($width, $height, $color)</td>
	<td>Draw triangle directed to bottom</td>
</tr>
</table>

Utils

<table>
<tr>
	<td></td>
	<td></td>
</tr>
</table>

### Changelog
2015.11.07
- partialization (primitives)

2015.05.09
- opacity

2015.05.09
- clearfix

2015.04.31
- Init
- linearGradientFromLeft
- linearGradientFromTop
- animateAll
