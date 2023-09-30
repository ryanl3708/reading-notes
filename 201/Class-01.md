## Reading Notes Class-01 ##

### Why this matters ###

### Javascript Basics ###
* Compose a short poem describing how HTTP sends data between computers.
A client comes-o-knockin'
In HTTP it asks for a copy
In TCP/IP the server heeds the call
And the server sends HTTP packets
And therein lies data to parse

* Describe how HTML, CSS, and JS files are “parsed” in the browser.
The browser parses the HTML file from the server, which contains a link element that has references to CSS and script (JS) elements. These links allow the browser to download and parse relevant CSS and JS files. 

* How can you find images to add to a Website?
Google search is the simplest. Simply avoid copyrighted material using google's license filter.

* How do you create a String vs a Number in JavaScript?
A string is enclosed in quote marks ('')
A number/integer can be turned into a string through concatenation (usually through addition), but subtraction turns string back into an integer in Javascript.

* What is a Variable and why are they important in JavaScript?
A variable is a way to store values, declared by the 'let' command.
The variable can be stored in may types (string, number, boolean, array, object).
Variables are important for dynamic programming in JavaScript, allowing users to get personalized outcomes based on the different inputs registered.

### HTML ###
* What is an HTML attribute?
An HTML attribute controls how the specific HTML element looks or behaves.
Defined in the opening tag with an attribute name and value.

* Describe the Anatomy of an HTMl element.
An HTML element has a content (usually text) enclosed within an opening and closing tag.
An element can be nested within an element, and an opening tag can have attributes adjusting the element's behavior.
There are exceptions like the Void element which is just a single tag.

* What is the Difference between <article> and <section> element tags?
Though the difference is mainly semantic, usually the Section tag is used to split a page by groups of content, while the article tag is used for enclosing blocks of content that can work independently.

* What Elements does a “typical” website include?
Generally a typical website has a head and body elements, in which lies the header and main elements (and nav, footer, and aside elements depending on the layout). Inside the main, subsections are created with use of div, section, and article elements.

* How does metadata influence Search Engine Optimization?
The description in the metadata is what Search Engine algorithm uses to determine if the website is relevant to a search inquiry. A good metadata will help with the website's visibility.

* How is the <meta> HTML tag used when specifying metadata?
Meta element encloses various attributes such as name and content.
These attributes can be used to specify the author, or give a brief description of the website (metadata) giving the search engine keywords to look for, and a summary to display to the user.

### MISC ###
* What is the first step to designing a Website?
Figuring out the purpose/goal of the website, and mapping out what needs to be put on the website to offer users what they need.

* What is the most important question to answer when designing a Website?
The most important question is how the website would help me reach my goals.

## Semantics ##
* Why should you use an <h1> element over a <span> element to display a top level heading?
Though span may be used, it is an inline element versus h1 being a semantic and block element. A semantic element makes the code significantly more readable, and will be prioritized by the search engine.

* What are the benefits of using semantic tags in our HTML?
Semantic tags are significantly more readable in code, makes it clear what type of data it will contain, and aids search engine in finding important keywords, making the website more visible.
