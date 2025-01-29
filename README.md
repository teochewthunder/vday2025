# Valentine's Day SVG Animation
This is an SVG with only inline CSS

## Animation steps:
1. Letters `I` and `U` are covered with red hearts.
2. Pink heart falls on top of red hearts.
3. Pink heart absorbs red hearts to grow bigger.
4. Final SVg reads `I &heart; U`.
5. Circles orbit the perimeter of pink heart indefinitely.

## Defs
- `textBackground`: Linear gradient transitions between white and pink for letters `I` and `U`.
- `redheartBackground`: Radial gradient transitions between red and brown for red hearts.
- `pinkheartBackground`: Radial gradient transitions between pink and deep pink for pink heart.

## Notes
- Transformation animations should have `transform-origin` attribute of element to be set to middle so as to more easily predict outcome of transformations.
- For subsequent transformation animations on the same element, `additive` attribute to be set to "sum".
