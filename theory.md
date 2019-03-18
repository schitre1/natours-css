`Three pillars to write good html / css`
- Responsive design
    - Fluid layouts
    - Media queries
    - Responsive images
    - Correct units
    - Desktop first vs mobile first
- Maintainable and Scalable Code
    - Clean
    - Easy to understand
    - Growth
    - Reusable
    - How to organize files
    - How to name classes
    - How to sctructure HTML
- Web performance
    - Less HTTP requests
    - Less code
    - Compress code
    - Use a CSS preprocessor
    - Less images
    - Compress images

`How CSS works behind the scenes?`

Load HTML -> Parse HTML -> **Document Object Model**

Parse HTML -> Parse CSS -> Resolve conflicts (cascade) -> Process final CSS values -> **CSS Object Model**

Models -> Render tree -> Website rendering the visal formatting model -> **Final rendered website**

`Importance` 
- User **!important** declarations
- Author **!important** declarations
- Author declarations
- User declarations
- Default browser declarations

`Specificity`
- Inline styles
- IDs
- Classes, pseudo classes, attribute
- Elements, pseudo-elements

`Source Order`
- The last declaration in the code will apply