## Reading Note Class 5

### Intro to CSS

### What is CSS (Cascading Style Sheets)
* CSS is a 'rule-based' language used in styling/laying out/adding effects to documents
    * (a document is a text file structured using markup language such as HTML)
* CSS Syntax
    * Use selectors and then curly braces {} to define CSS application range
    * within the braces, write declarations (which is a pair of property and value)
* CSS modules - the way CSS language is sorted/broken down into
* CSS specifications - just check how CSS Working Group developed it.

### How to add CSS
* 3 ways of insterting style sheet
    * External, Internal, Inline
* External CSS
    * make a separate .css file including css formatting instructions
    * Use link to call in .css formatting instructions in the html file
* Internal CSS
    * Define inside the Style element in the head section of HTML file.
* Inline CSS
    * Apply unique style for a single element

#### CSS properties
* If multiple style sheets overlap, the last used one will be expressed
* Cascading Order (style priority)
    * Inline Style > External/internal style sheet > browser default
* CSS color property
    * sets text-color for different elements
    * color with HEX, RGB, RGBA, HSL, HSLA etc...
    * color: value