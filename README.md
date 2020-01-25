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

### Install with npm

```npm
$ npm install @space-css/space-css@1.0.0
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

### 1.Property prefix

```css
sp  =   space
m   =   margin
p   =   padding

```

All properties have !important as you should only add those classes, if you definitely want a specific behavior.

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

#### Viewport classes

```css
.sp-min-vw-10 - min view width .sp-min-vh-100 - min view height .sp-vw-100 -
  view width .sp-vh-100 - view height;
```

### Margin Classes

#### Margin Classes With Range Of 0-10

```css
.sp-m- (0-10) .sp-mt- (0-10) .sp-my- (0-10) .sp-mr- (0-10) .sp-mx- (0-10)
  .sp-mb- (0-10) .sp-my- (0-10) .sp-ml- (0-10) .sp-mx-;
```

#### Margin NEGATIVE Classes With Range Of 0-10

```css
.sp-m-n (0-10) .sp-mt-n (0-10) .sp-my-n (0-10) .sp-mr-n (0-10) .sp-mx-n (0-10)
  .sp-mb-n (0-10) .sp-my-n (0-10) .sp-ml-n (0-10) .sp-mx-n (0-10);
```

#### Margin Auto

```css
.sp-m-auto .sp-mt-auto .sp-my-auto .sp-mr-auto .sp-mx-auto .sp-mb-auto, .sp-my-auto
    .sp-ml-auto .sp-mx-auto;
```

### Margin Classes For {SM} @media (min-width: 576px) {} screens With Range Of 0-10

```css
.sp-m-sm (0-10) .sp-mt-sm (0-10) .sp-my-sm (0-10) .sp-mr-sm (0-10) .sp-mx-sm
  (0-10) .sp-mb-sm (0-10) .sp-my-sm (0-10) .sp-ml-sm (0-10) .sp-mx-sm;
```

#### Margin NEGATIVE Classes For {SM} @media (min-width: 576px) {} screens With Range Of 0-10

```css
.sp-m-sm-n (0-10) .sp-mt-sm-n (0-10) .sp-my-sm-n (0-10) .sp-mr-sm-n (0-10)
  .sp-mx-sm-n (0-10) .sp-mb-sm-n (0-10) .sp-my-sm-n (0-10) .sp-ml-sm-n (0-10)
  .sp-mx-sm-n (0-10);
```

#### Margin AUTO Class For {SM} @media (min-width: 576px) {} screens

```css
.sp-m-sm-auto .sp-mt-sm-auto .sp-my-sm-auto .sp-mr-sm-auto .sp-mx-sm-auto
    .sp-mb-sm-auto, .sp-my-sm-auto .sp-ml-sm-auto .sp-mx-sm-auto;
```

### Margin Classes For {MD} @media (min-width: 768px) {} screens With Range Of 0-10

```css
.sp-m-md (0-10) .sp-mt-md (0-10) .sp-my-md (0-10) .sp-mr-md (0-10) .sp-mx-md
  (0-10) .sp-mb-md (0-10) .sp-my-md (0-10) .sp-ml-md (0-10) .sp-mx-md;
```

#### Margin NEGATIVE Classes For {MD} @media (min-width: 768px) {} screens With Range Of 0-10

```css
.sp-m-md-n (0-10) .sp-mt-md-n (0-10) .sp-my-md-n (0-10) .sp-mr-md-n (0-10)
  .sp-mx-md-n (0-10) .sp-mb-md-n (0-10) .sp-my-md-n (0-10) .sp-ml-md-n (0-10)
  .sp-mx-md-n;
```

#### Margin AUTO Class For {MD} @media (min-width: 768px) {} screens

```css
.sp-m-md-auto .sp-mt-md-auto .sp-my-md-auto .sp-mr-md-auto .sp-mx-md-auto
    .sp-mb-md-auto, .sp-my-md-auto .sp-ml-md-auto .sp-mx-md-auto;
```

### Margin Classes For {LG} @media (min-width: 992px) {} screens With Range Of 0-10

```css
.sp-m-lg (0-10) .sp-mt-lg (0-10) .sp-my-lg (0-10) .sp-mr-lg (0-10) .sp-mx-lg
  (0-10) .sp-mb-lg (0-10) .sp-my-lg (0-10) .sp-ml-lg (0-10) .sp-mx-lg;
```

#### Margin NEGATIVE Classes For {LG} @media (min-width: 992px) {} screens With Range Of 0-10

```css
.sp-m-lg-n (0-10) .sp-mt-lg-n (0-10) .sp-my-lg-n (0-10) .sp-mr-lg-n (0-10)
  .sp-mx-lg-n (0-10) .sp-mb-lg-n (0-10) .sp-my-lg-n (0-10) .sp-ml-lg-n (0-10)
  .sp-mx-lg-n (0-10);
```

#### Margin AUTO Class For {LG} @media (min-width: 992px) {} screens

```css
.sp-m-lg-auto .sp-mt-lg-auto .sp-my-lg-auto .sp-mr-lg-auto .sp-mx-lg-auto
    .sp-mb-lg-auto, .sp-my-lg-auto .sp-ml-lg-auto .sp-mx-lg-auto;
```

### Margin Classes For {XL} @media (min-width: 1200px) {} screens With Range Of 0-10

```css
.sp-m-xl (0-10) .sp-mt-xl (0-10) .sp-my-xl (0-10) .sp-mr-xl (0-10) .sp-mx-xl
  (0-10) .sp-mb-xl (0-10) .sp-my-xl (0-10) .sp-ml-xl (0-10) .sp-mx-xl;
```

#### Margin NEGATIVE Classes For {XL} @media (min-width: 1200px) {} screens With Range Of 0-10

```css
.sp-m-xl-n (0-10) .sp-mt-xl-n (0-10) .sp-my-xl-n (0-10) .sp-mr-xl-n (0-10)
  .sp-mx-xl-n (0-10) .sp-mb-xl-n (0-10) .sp-my-xl-n (0-10) .sp-ml-xl-n (0-10)
  .sp-mx-xl-n (0-10);
```

#### Margin AUTO Class For {XL} @media (min-width: 1200px) {} screens

```css
.sp-m-xl-auto .sp-mt-xl-auto .sp-my-xl-auto .sp-mr-xl-auto .sp-mx-xl-auto
    .sp-mb-xl-auto, .sp-my-xl-auto .sp-ml-xl-auto .sp-mx-xl-auto;
```

### Padding Classes

```css
.sp-p- (0-10) .sp-pt- (0-10) .sp-py- (0-10) .sp-pr- (0-10) .sp-px- (0-10)
  .sp-pb- (0-10) .sp-py- (0-10) .sp-pl- (0-10) .sp-px-;
```

### Padding Classes For {SM} @media (min-width: 576px) {} screens With Range Of 0-5

```css
.sp-p-sm (0-5) .sp-pt-sm (0-5) .sp-py-sm (0-5) .sp-pr-sm (0-5) .sp-px-sm (0-5)
  .sp-pb-sm (0-5) .sp-py-sm (0-5) .sp-pl-sm (0-5) .sp-px-sm;
```

#### Padding AUTO Class For {SM} @media (min-width: 576px) {} screens

```css
.sp-p-sm-auto .sp-pt-sm-auto .sp-py-sm-auto .sp-pr-sm-auto .sp-px-sm-auto
    .sp-pb-sm-auto, .sp-py-sm-auto .sp-pl-sm-auto .sp-px-sm-auto;
```

### Padding Classes For {MD} @media (min-width: 768px) {} screens With Range Of 0-5

```css
.sp-p-md (0-5) .sp-pt-md (0-5) .sp-py-md (0-5) .sp-pr-md (0-5) .sp-px-md (0-5)
  .sp-pb-md (0-5) .sp-py-md (0-5) .sp-pl-md (0-5) .sp-px-md;
```

#### Padding AUTO Class For {MD} @media (min-width: 768px) {} screens

```css
.sp-p-md-auto .sp-pt-md-auto .sp-py-md-auto .sp-pr-md-auto .sp-px-md-auto
    .sp-pb-md-auto, .sp-py-md-auto .sp-pl-md-auto .sp-px-md-auto;
```

### Padding Classes For {LG} @media (min-width: 992px) {} screens With Range Of 0-5

```css
.sp-p-lg (0-5) .sp-pt-lg (0-5) .sp-py-lg (0-5) .sp-pr-lg (0-5) .sp-px-lg (0-5)
  .sp-pb-lg (0-5) .sp-py-lg (0-5) .sp-pl-lg (0-5) .sp-px-lg;
```

#### Padding AUTO Class For {LG} @media (min-width: 992px) {} screens

```css
.sp-p-lg-auto .sp-pt-lg-auto .sp-py-lg-auto .sp-pr-lg-auto .sp-px-lg-auto
    .sp-pb-lg-auto, .sp-py-lg-auto .sp-pl-lg-auto .sp-px-lg-auto;
```

### Padding Classes For {XL} @media (min-width: 1200px) {} screens With Range Of 0-5

```css
.sp-p-xl (0-5) .sp-pt-xl (0-5) .sp-py-xl (0-5) .sp-pr-xl (0-5) .sp-px-xl (0-5)
  .sp-pb-xl (0-5) .sp-py-xl (0-5) .sp-pl-xl (0-5) .sp-px-xl;
```

#### Padding AUTO Class For {XL} @media (min-width: 1200px) {} screens

```css
.sp-p-xl-auto .sp-pt-xl-auto .sp-py-xl-auto .sp-pr-xl-auto .sp-px-xl-auto
    .sp-pb-xl-auto, .sp-py-xl-auto .sp-pl-xl-auto .sp-px-xl-auto;
```

## Notes

All space css class properties have !important as you should only add those classes, if you definitely want a specific behavior.

Width & Heights Sizes are defined in:

```css
%
```

While Margin and Padding sizes are defined in

```csss
rem
```

But why rem?
Our primary purpose of using rem is to ensure that whatever default font size a user has their browser set to, the layout will adjust to accommodate the size of text or elements within it.

If you want the the class on just one screen size, you need to set the other classes to default(0)

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)

## Authors

Made with 💜 By [Oluwatobi Ishola](http://twitter.com/mroluwatobby) & [Folorunso Adesanya](http://twitter.com/devfolorunso)
