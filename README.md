GitBook Plugin for Customized Table of Contents Headings
========================================================

Install it using: ```$ npm install gitbook-plugin-tocstyles```

Be sure too activate the option from the `book.json` file :

```json
{
  "plugins"       : ["tocstyles"]
  ,"pluginsConfig":
  {
    "tocstyles" : [ "", "decimal-leading-zero", "circle" ]
  }
}
```

The `tocstyles` array in `pluginsConfig` defines [CSS list-style-type properties](http://www.w3.org/TR/css-counter-styles-3/#counter-style) for each level of the TOC hierarchy.

## License: MIT

http://clkao.mit-license.org/
