## Reading Note Class 6

## Javascript (JS)

### Javascript Intro
* Javascript is a lightweight, interpreted, and just-in-time compiled programming language with first-class functions
    * "asynchronous, dynamically-typed, interpreted scripting language"
    * first class functions means the language treats functions like variables, and can be passed as an argument to other functions/assigned as a variable etc.
    * 'just in time' compilation = compiles while running the program.
* Javascript is also a prototype-based, multi-paradigm, single-threaded, dynamic language, and supports object-oriented, imperative, and declarative styles.
* used in Node.js, JQuery, Angular.js etc..
* 3 ways Javascript is used
    * language itself, DOM API, and server API

### Basic Javascript usage
* Can use any text editor
* can either 
    * embed JavaScript code directly inside HTML
        * use 'script language="javascript"  /script' opening and closing tags
    * put a line in HTML to include external JavaScript file
* Output:
    * 'alert("textwhatever") = prints textwhatever
    * 'document.write("(formatting) textwhatever (/formatting)"); 
        * embeds textwhatever between html lines before and after
        * used when looking to change what's shown.
* console.log
    * prints out debugging information
    * just type console.log("text");

### Basic Javascript input w/prompt & confirm

* Prompt
    * shows a pop-up window with text provided as first parameter
    * and provides a textbox the user can fill in.
    *      var name = prompt("question :", "");
            document.write("text ", name);
        * stores response "" as name variable, prints name
    * function returns null if user cancels/escs

* Confirm
    * user click ok then returns 'true', if cancel/esc then 'false'
    * used for if/else statements

### Variables
* data types
    * strings (text values) : written inside double or single quotes ("''")
* variables are containers for storing data (values)
* all variables must be identified with unique names
    * unique names : "identifiers"
    * can contain letters, digits, underscores, and dollar signs
    * must begin with a letter, or $ and _
    * case sensitive
    * reserved words cannot be used
* can be undeclared, or declared with 'let', 'var', 'const'
    * cannot use 'let' or 'const' in 2015 or older javascript
    * cannot redeclare with 'let' or 'const'
* always declare with 'const' UNLESS:
    * if value of variable can change, then use 'let'
    * const cant be changed.
* = is an assignment operator, not equal to.
    * assigns value to variable in left.
* declaring a variable has no value until assigned. (Undefined)
* can assign multiple variables in one statement
    *       i.e. let person = "ABC", carName = "BBC", price = 200;

Arithmetic
* if mixing strings with other var, concatenated
    * Everything turns into strings immediately near and after string
    * 5 + "5" + 2 + 3 = 5523
    * BUT arithemetic BEFORE string done normally
    * 5 + 3 + "3" + 2 = 832

