# changePage.js

Change "page" without reloading site

---

[*index.html*](https://github.com/magarenzo/change-page/blob/master/index.html) provides a template to see how [*changePage.js*](https://github.com/magarenzo/change-page/blob/master/changePage.js) works

## How it works

Use *onclick* event of *a* element to pass in name of *div* we want to display

```html
<a onclick="changePage(event, 'about');">About Me</a>
```

*div* being passed to *changePage.js* needs to have *class="section"*

```html
<div id="about" class="section"></div>
```

Sections we don't want displayed before clicking its corresponding link to show it should start with *display: none;* and we should display the first section we want showing, if any

```css
.section { display: none; }
#home { display: block; }
```

## Created with

* [`JavaScript`](https://www.javascript.com/)

## Owner

Michael A. Agarenzo
