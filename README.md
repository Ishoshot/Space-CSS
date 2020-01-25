# @space-css/space-css

![NPM](https://img.shields.io/npm/l/@space-css/space-css) ![npm (scoped)](https://img.shields.io/npm/v/@space-css/space-css)

Space CSS is a highly responsive mordern trend spacing library for margins, paddings and more..

## Usage

```html
<head>
  <!-- other stuff -->
  <link
    rel="stylesheet"
    href="https://unpkg.com/@space-css/space-css@1.1.0/space.css"
  />
</head>
```

## Install with npm

```npm
npm install @space-css/space-css@1.0.0
```

These elements have no padding:

```html
<body>
  <h1 class="sp-p-0">Lorem ipsum</h1>
  <h2 class="sp-p-0">Dolor sit</h2>
</body>
```

This navigation is centered:

```html
<body>
  <nav class="sp-m-auto">
    <a href="/">Home</a>
  </nav>
</body>
```

## How it works

All classes are composed of some simple parts.

### 1. Property prefix

```css
m   =   margin
________________
p   =    padding

```

### 2. Possible classes (normal syntax)

Margin classes (they start with m) can have positive and negative values, padding classes (replace the leading m with a p) only have positive values.

Width and Height Sizes are specified in %
sp: coined from the word space css
h: height
w: width
mh: max-height
mw: max-width

#### Traditional width classes

```css
.sp-w-20 .sp-w-30 .sp-w-40 .sp-w-50 .sp-w-60 .sp-w-70 .sp-w-80 .sp-w-90
  .sp-w-100 .sp-w-auto .sp-mw-100;
```

#### Traditional height classes

```css
.sp-h-20 .sp-h-30 .sp-h-40 .sp-h-50 .sp-h-60 .sp-h-70 .sp-h-80 .sp-h-90
  .sp-h-100 .sp-h-auto .sp-mh-100;
```

#### Viewport lenght

```css
.sp-min-vw-10 - min view width .sp-min-vh-100 - min view height .sp-vw-100 -
  view width .sp-vh-100 - view height;
```

## Notes

All space css class properties have !important as you should only add those classes, if you definitely want a specific behavior.

Width & Heights Sizes are defined in:

```css
%
```

While Margins and Paddings
are defined in

```csss
rem
```

But why rem?
Our primary purpose of using rem units is to ensure that whatever default font size a user has their browser set to, the layout will adjust to accommodate the size of text or elements within it.

If you want the the class on just one screen size, you need to set the other classes to default(0)

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)

## Authors

1. [Oluwatobi Ishola](http://twitter.com/mroluwatobby)

2. [Folorunso Adesanya](http://twitter.com/devfolorunso)
