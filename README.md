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
  <h1 class="p-0">Lorem ipsum</h1>
  <h2 class="p-0">Dolor sit</h2>
</body>
```

This navigation is centered:

```html
<body>
  <nav class="m-auto">
    <a href="/">Home</a>
  </nav>
</body>
```

## How it works

All classes are composed of some simple parts.

### 1.Property prefix

```css
m       =   margin
___________________
p   =    padding

```
All properties have !important as you should only add those classes, if you definitely want a specific behavior.

Sizes are defined in:

```css
rem
```

## Notes

You must specify for all the screen sizes else it will take the single class you have specified as all,

If you want the the class on just one screen size, you need to set the other classes to default(0)

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)

## Authors

1. [Oluwatobi Ishola](http://twitter.com/mroluwatobby)

2. [Folorunso Adesanya](http://twitter.com/devfolorunso)
