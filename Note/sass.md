# SASS

- A css preprocessor, an extension of CSS that adds power and elegance to the basic language.
- Sass compiler compiles SASS source code to compiled CSS code.

## Two Kinds of SASS Syntax

### SASS

```sass
.navigation
    list-style: none
    float: left

    &li
        display: inline-block
        margin-left: 30px
```

### SCSS

```scss
.navigation {
    list-style: none;
    float: left;

    & li {
        display: inline-block;
        margin-left: 30px;
    }
}
```

- This course uses SCSS.

## SASS Features

- Variables
- Nesting
- Operators
- Partials and imports
- Mixins
- Functions
- Extends
- Control directives

## Mixin VS Extend

- Mixin copys the parent properties to the child class
- Extend copy the child properties to the parent class.
- Use Extend when the selector or the element that we are extending are related to one another.
