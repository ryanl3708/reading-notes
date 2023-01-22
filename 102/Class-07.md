## Reading Notes Class 7

## Programming with Javascript

### Control Flow
* is the order in which computer executes statements in a script
* code runs in order from first line to last line, unless structures change control flow (i.e. conditionals and loops and calling functions)
* look at program structure and see how it affects order of execution.

### JavaScript Functions
* block of code designed to perform a particular task
    * executed when something calls it
    * reuseable, so can be used by different arguments

#### JavaScript function syntax
* can include multiple parameters within parenthesis
*       function name(p1, p2, p3, parameters....) {
            return p1 * p2 * p3 ....
        }
* parameters listed inside parenthesis (parameter1....)
* Function arguments are the values received by the function when it is invoked
* inside the function {}, arguments (parameters) behave as local variables
#### Function invocation
* occurs when :
    * when an event occurs (user interaction)
    * when it is invoked (called) from JavaScript code
    * automatically (self-invoked)

#### Function return
* 'return' statement stops function from executing.
* return value returned back to caller after computing.

*       function myFunction(p1, p2) {
            return p1 * p2
        }
        document.getElementById("demo").innerHTML = myFunction(5,8)
        
        * if no (5,8) behind myFunction, spits out myFunction as object (entire 'return p1*p2 gets printed)
Function----
* Function can be used as variables
* variables declared within function becomes LOCAL to function (local variables)

#### Operators
Type of operators
* assignment ( = )
* Addition ( + )
* Multiplication ( * )
* Exponentiation ( ** )  --- 2016 yr and newer
* Division ( / )
* Modulus ( % )  -- division remainder (gives remainder from division)
* Increment ( ++ )
* Decrement ( -- )

Javascript assignment operators
* can combine above operators with '=' like +=, /= etc..
* += can be used to concatenate (add) strings

Comparison operators
* ==
* ===
* !=
* !==
* '>'
* <
* '>='
* <=
* ?  ternary operator

Logical Operator
* &&  and
* ||  or
* !   not

Type operator
* typeof   -  returns type of variable
* instanceof  -  returns true if object is an instance of an object type

Bitwise operator (works on 32bit numbers)
* whats the use for this?