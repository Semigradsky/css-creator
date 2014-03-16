css-creator
===========

JS library for dynamically creating CSS on page.

## Installation

```
$ bower install css-creator
```

## Usage

```
var globalStyles = new CSSCreator();
...
globalStyles.addRules([
  ['h2',
    ['color', 'red'],
    ['background-color', 'green', true] // 'true' for !important rules 
  ], 
  ['.myClass', 
    ['background-color', 'yellow']
  ]
]);
...
globalStyles.addToPage();
```

For more examples see example.html file.

# License

Code is released under [the MIT license](LICENSE).