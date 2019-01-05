# Typography.js
A powerful toolkit for building websites with beautiful responsive typography.
This is a fork of the prolific Kyle Matthews excellent [typography.js](https://github.com/KyleAMathews/typography.js) library with added breakpoints support.

Usage should be the same as the regular lib but with an added breakpoints setting:
```js
const typeConfig = {
  bodyFontFamily: ["Josefin Sans", "sans-serif"],
  headerFontFamily: ["Libre Franklin", "sans-serif"],
  bodyWeight: 100,
  headerWeight: 400,
  baseFontSize: "18px",
  baseLineHeight: 1.6,
  scaleRatio: 1.5,
  blockMarginBottom: 1,
  includeNormalize: false,
  breakpoints: {
    "@media screen and (min-width: 700px)": {
      baseFontSize: "20px",
      scaleRatio: 1.8
    },
    [`@media screen and (min-width: ${breakpoint.large})`]: {
      baseFontSize: "22px",
      scaleRatio: 1.9
    }
  }
}
```
