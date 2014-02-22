#Angular variables inside style blocks

This small directive allows angular variables to be evaluated into style blocks.

e.g.

```css
<style>
	body {
		background-color:{{bgColor}};
	}
</style>
```

With the variable bgColor available in some parent scope.

##Usage
- Include dmStyle.js
- Add dm.style as a dependency to your app module.

Thats it! This will automatically start compiling inline CSS.
