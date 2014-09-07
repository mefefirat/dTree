# jQuery Tree Menu

A tree menu plugin for jQuery framework

[![GitHub version](https://d25lcipzij17d.cloudfront.net/badge.svg?id=gh&type=5&v=1.0)](https://github.com/mefefirat/dTree)

## Examples
http://jsfiddle.net/nnLg07ag/10/

### HTML

```html
<div class="dTree">
<ul>
	<li><a href="#">Fiat</a>
		<ul>
			<li><a href="#">Kartal SLX</a></li>
			<li><a href="#">Dogan 1.6 Turbo</a></li>
			<li><a href="#">Sahin</a></li>
			<li class="active"><a href="#">Dogan Gorunumlu Sahin</a>
				<ul>
					<li><a href="#">1.3 Motor</a></li>
					<li><a href="#">1.6 Motor</a></li>
					<li><a href="#">1.8 Motor</a></li>
					<li><a href="#">2.0 Motor</a></li>
				</ul>
			</li>
			<li><a href="#">Serce</a></li>
			<li><a href="#">Murat 131</a></li>
		</ul>
	</li>
	<li><a href="#">Fiat</a>
		<ul>
			<li><a href="#">Kartal SLX</a></li>
			<li><a href="#">Dogan 1.6 Turbo</a></li>
			<li><a href="#">Sahin</a></li>
			<li class="active"><a href="#">Dogan Gorunumlu Sahin</a>
				<ul>
					<li><a href="#">1.3 Motor</a></li>
					<li><a href="#">1.6 Motor</a></li>
					<li><a href="#">1.8 Motor</a></li>
					<li><a href="#">2.0 Motor</a></li>
				</ul>
			</li>
			<li><a href="#">Serce</a></li>
			<li><a href="#">Murat 131</a></li>
		</ul>
	</li>
</ul>
</div>
```
### 3.Call the plugin

```html
$(document).ready(function(){
	$(".dTree").dTree();
});  
```
