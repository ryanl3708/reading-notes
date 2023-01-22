## Reading Note Class 4

### Wireframe and Design

* Wireframe is used to plan out the outline or basic design and the interactibility of a website or an app.
* Sketch -> Wireframe -> Interactive prototype -> Visual -> Code (steps can be added or skipped)
* Map out the user flow & information architecture before sketching.
* Good wireframes have :
    * Clarity
    * Confidence
    * Simplicity
* Online Wireframe tools : [UXPin](https://www.uxpin.com/), [InVision](http://www.invisionapp.com/), [Wireframe.cc](https://wireframe.cc/)

### HTML Basics

* [Anatomy of an HTML element](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics/grumpy-cat-small.png)
    * Opening tag
    * Closing tag
    * Content
    * Element (all of the above)
    * [Attributes](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics/grumpy-cat-attribute-small.png) (contains extra information about the element)
        * Attributename="attributevalue">
* Nesting elements
    * Make sure one element is clearly inside the other in proper order.
* Void elements
    * elements with no content (i.e. img element) and doesn't wrap content
    * img used as (img src="linktoimagesource" alt="name/descrioption" /)
        * alt is description of image
* Anatomy of an HTML Document
    * !DOCTYPE html - always at top
    * html/html  -  html element wrapping all content in entire page (Known as roote element)
    * head/head  -- not visible to readers, contains all content like style/ keywords etc
    * meta charset="utf-8" /   -- sets all characters in doc to this setting
    * meta name="viewport" content="width=device-width"  --fits to device page screen by shrinking
    * title/title -- title for page
    * body/body -- body of content
    * h1~h6 for heading levels for headers
    * p/p for paragraphs
    * unordered (ul) vs ordered lists (ol)
        * use (li) within ul or ol listings
    * a/a links -- used as (a href="link")(/a)

#### Semantics
* Semantic element : element that clearly defines its content/meaning to both the browser and the developer
* Benefits : 
    * Simpler organization (blocks of code grouped up)
    * Keywords better found by search engines
    * semantic namings mirror proper custom element/component naming
* Examples :
    * article, aside, details, figcaption, figure, footer, header, main, mark, nav, section, summary, time
* HTML section element:
    * "thematic grouping of content, typically with a heading"
* HTML article element:
    * specifies independent, self-contained content (should be possible to distribute independently from the rest of the site)
