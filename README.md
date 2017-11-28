# ![](assets/icon.png) Stylist

A collection of stylus functions and mixins to build web applications.

## How to use

Install with NPM

```bash
npm install stylist-css --save
```

Use a CDN

- [https://unpkg.com/stylist-css/stylist.css](https://unpkg.com/stylist-css/stylist.css)

## Example

View [demo](https://jabes.github.io/stylist/).

#### Grid

```html
<link rel="stylesheet" href="stylist.css">
<div class="container">
  <div class="row">
    <div class="col-xs-12 col-md-6 col-lg-4"></div>
    <div class="col-xs-12 col-md-6 col-lg-4"></div>
    <div class="col-xs-12 col-md-6 col-lg-4"></div>
  </div>
</div>
```

#### Flexible Box

```html
<link rel="stylesheet" href="stylist.css">
<div class="flex">
  <div class="flex-none"></div>
  <div class="flex-auto"></div>
</div>
```
