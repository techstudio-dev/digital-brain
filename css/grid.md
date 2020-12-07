# CSS Grid

## Current weird problems

### SVGs loading with a delay

I had the problem that my SVGs were loaded a second later than the grid showed up. It looks like the browser rendering is doing something different with SVGs when using the grid than flexbox. After reworking my component with flexbox the SVG delay disappeared.
