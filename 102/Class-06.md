## Reading Note Class 6

## Javascript (JS)

### Javascript Intro
* Javascript is a lightweight, interpreted, and just-in-time compiled programming language with first-class functions
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