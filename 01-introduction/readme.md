# Introduction
## What is scss / sass
    - Syntactically Awesome Style Sheets
    - Different approach of writing CSS
    - easier to write & maintain
    - needs a compiler
    - features:
        - variables
        - nesting
        - mixins
        - functions
        - inheritance / abstraction
        
## Differences between scss / sass
#### SASS
```sass
$font-stack: Helvetica, sans-serif
$primary-color: #333

body
  font: 100% $font-stack
  color: $primary-color
```
#### SCSS
```scss
$font-stack: Helvetica, sans-serif;
$primary-color: #333;

body {
  font: 100% $font-stack;
  color: $primary-color;
}
```

## How does it work
    - write scss
    - compile
    - css <3
    
## Play ground
`npm i`
`sass [folder]/index.scss [folder]/index.css`