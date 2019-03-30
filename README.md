# ![icon](https://github.com/icy-flame/css-uwp/raw/master/css-uwp.png)&nbsp;&nbsp;CSS-UWP
UWP controls in a light CSS file.
## Getting Started
Download `css-uwp.css` and add the following element to your HTML pages. (Change `href` as needed)  
```
<link rel="stylesheet" type="text/css" href="./css-uwp.css" />
```
If you want to change the accent color, add the following code to your HTML pages and replace `0,120,215` with the RGB value you want.
```
<style type="text/css">
    html {
        --accent-color: 0,120,215;
    }
</style>
```
## Components
### HR
```
<hr>
```
### Hyperlink
```
<a href="">Hyperlink</a>
```
### Button
Gray
```
<button class="uwp-button-negative">Button</button>
```
Colored
```
<button class="uwp-button-positive">Button</button>
```
### Checkbox
```
<label class="uwp-checkbox"><input type="checkbox"><span class="uwp-checkmark"></span>Checkbox</label>
```
### Radio Button
```
<label class="uwp-checkbox"><input type="radio" name="radio"><span class="uwp-radiomark"></span>Radio Button</label>
```
### Toggle
```
<label class="uwp-toggle"><input type="checkbox"><span class="uwp-toggleslider"></span></label>
```
### Textbox
```
<input type="text" placeholder="Textbox" class="uwp-textbox">
```
### Select
```
<select class="uwp-select">
    <option selected>Select 1</option>
    <option>Select 2</option>
    <option>Select 3</option>
</select>
```
### Range
```
<input type="range" class="uwp-slider">
```
## Demo
[CSS-UWP Demo](https://icyflame.cn/css-uwp)
