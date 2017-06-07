## Hipspot Critique

HTML Inconsistencies:
- Email input uses `input type="text"`, should be `input type="email"`
- Submit button uses `input type="button"`, should be `input type="submit"`

CSS Inconsistencies:
- `'Droid Sans Mono',` misspelled under `body`
- `margin: 0;` not present under `body`
- `.intro {padding: 0;}` overwrites correct styling
- `fieldset` `border` should be set to `dashed`
- The `color` property on `input[type="submit"]` overwrites the correct `color` property on `.button`
- `input[type]` selector provides `width: 100%;` to all of the inputs but overwrites padding
- `min-height: 100vh;` missing from `.background`
- `padding-bottom: 2rem` missing from `.background`
