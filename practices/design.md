# Design practices

## Design

- Prefer [Sketch](http://bohemiancoding.com/sketch/) for UI design
- Prefer [ionicons](http://ionicons.com/) for UI icons (instead of FontAwesome)
- Prefer [Styledown](https://github.com/styledown/styledown) for making a Living Styleguide

## Sass/CSS

- Prefer `.scss` (nested) syntax over `.sass` (indented), since most projects use that
- Enable [CSS antialiasing](http://ricostacruz.com/cheatsheets/css-antialias) globally
- Prefer to make new components rather to extend/override Bootstrap components
- Prefer to break CSS into multiple files and use `@import 'components/*'` ([info](https://github.com/rstacruz/rscss#one-component-per-file))
- Prefer to start a styleguide as early on in the project
- Refer to [rscss](http://rscss.io)
- The rscss [two-word rule](https://github.com/rstacruz/rscss#naming-components) isn't generally followed around here, feel free to break it
- Style `&:focus, &:hover { ... }` together
- If you've never broken the rule above, feel free to use `:focus { outline: none }` ([haha](http://www.outlinenone.com/))

## Bootstrap

- Refer to [bootstrap-practices](https://github.com/rstacruz/bootstrap-practices)
