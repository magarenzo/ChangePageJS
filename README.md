# ChangePageJS &#128195;

Change page without reloading site

![GIF of ChangePageJS in action](/media/ChangePageJS.gif)

## Demo

https://magarenzo.com/projects/ChangePageJS/

## Usage

Use `onclick` event of `a` element to pass in `id` of `<div>` we want to display

```html
<a onclick="changePage(event, 'skills');">Skills</a>
```

`<div>` being passed to `ChangePageJS` needs to have `class="section"`

```html
<div id="skills" class="section"></div>
```

Sections we don't want displayed before clicking its corresponding link to show it should start with `display: none;` and we should display the first section we want showing, if any

```css
.section { display: none; }
#about { display: block; }
```

## Used By

[magarenzo.com](https://magarenzo.com)

## Owner

Michael A. Agarenzo

[&#127867; Buy me a cider, or three!](https://www.buymeacoffee.com/magarenzo)
