## Class 8 notes

## Operators and Loops

### Operators

Rules

* unary vs binary operators
    * operation within one vs between multiple operands.
* precedence of certain operators (* / etc)

Assignment Operator
* right associative
*       y = x = f() is equivalent to y = (x=f())
* Avoid assignment chains!@

Comparison operator
* compares the operands and returns a logical value based on true/false
* if not the same type, JavaScript converts (usually to numerical)
    * unless using === or !== which checks for type too

Arithmetic Operator
* takes numerical values as operands and returns a single numerical value

Bitwise Operator
* treats operands as a set of 32 bits, but returns JavaScript numerical values

Bitwise shift Operator
* takes two operands, first being the number to be shifted, and second specifying how many positions to be shifted.
* ;eft/right/zero fill right shift

Logical Operator
* Logical AND (&&)  - true only if both true
* Logical OR (||)  - true if any true
* Logical NOT (!)

String Operators
* Can use + or += to concatenate strings

Comma Operators
* comma allows multiple operands to be used

Unary Operators
* Delete 
    * delete object.property;
        * deletes the property of an object (undefined afterwards)

* Typeof
    * typeof operand
        * displays type of object
* this expression
    * this.propertyname

### Loops and Iteration

for Statement
* Loop repeats until specified condition ends as 'False'
*       for ([initialExpression]; [conditionExpression]; [incrementExpression])
            statement

do...while Statement
* repeats until specified condition leads to false
*       do
            statement
        while (condition);

While Statement
* executes as long as specified condition is true
*       while (condition)
            Statement
* can cause infinite loops (careful)

Labeled Statement
* provides a statement with an identifier that lets you refer it elsewhere
*       label:
            Statement

Break Statement
* break can end a loop
*       break;

Continue Statement
* continue can be used to restart a while, do-while, for, or label statement

for-in statement
* iterates a specific variable over all enumerable properties of an object
*       for (variable in object)
            statement

For-of
    *creates a loop iterating over iterable objects