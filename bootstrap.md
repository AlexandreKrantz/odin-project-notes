# Bootstrap Notes
- Bootstrap grid system is based on flexbox. You use `.row` or `.col` to specify the flex-direction, then you can put any element within it. To make a grid, you but `.col` divs within a `.row`.
    - Rows should always be wrappers for columns when making a grid.
    - Content should always go withing columns.
    - 12 cols available by default in a row before wrapping.
    - There are bootstrap classes for columns that provide the different flexbox properties like justify-content, wrapping, gutters etc.
- container-sm, md, lg, etc affects max-width (before that, width = 100%).
- col-sm, md, lg, etc affects at which point the width will stop being 100%. Eg: col-sm-8 will have width 100% for small screens and then width 8/12 afterwards.
    - you can also combine different stuff, Eg: Columns start at 50% wide on mobile and bump up to 33.3% wide on desktop with `col-6 col-md-4`.
- Hierarchy: container -> row -> col -> content
- 
