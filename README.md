# typeface-vag-rounded

The CSS and web font files for the VAG Rounded typeface

## Install

`npm install --save @south-paw/typeface-vag-rounded`

or

`yarn add @south-paw/typeface-vag-rounded`

## Use

This project assumes that you're using webpack to process CSS and files.

The package includes the necessary font files (woff2, woff) and a CSS file with font-face declarations pointing at these files.

You will need to have webpack setup to load css and font files.

Many tools built with Webpack will work out of the box with this package such as [Gatsby](https://github.com/gatsbyjs/gatsby) and [Create React App](https://github.com/facebook/create-react-app).

To use, simply require the package in your project's entry file:

```js
// Load VAG Rounded typeface
require("@south-paw/typeface-vag-rounded");
```

and then apply the font family via CSS:

```css
body {
  font-family: "VAGRounded";
}
```

Package includes `100`, `400`, `700`, `900` font weights.

## Source

Package is inspired by the [typefaces project](https://github.com/KyleAMathews/typefaces).
