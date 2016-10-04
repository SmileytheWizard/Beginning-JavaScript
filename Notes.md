*/ Chapter 1
There are six value types in JavaScript :
Numbers, Strings, Booleans, Objects, Functions, and Undefined

Unary Operators: Operators that only use one value eg.(console.log( - value);) > -value
Binary Operators: Operators that use two values eg.(console.log( 4 * 7);) > 28
Ternary Operators: There is only one ternary operator in JavaScript the conditional operator.
       (console.log(Boolean ? value1 : value2);)
       If Boolean is true then console.log will return value1 else it will return value2

= is declaring a value
== is a Boolean; is equal to
=== is a Boolean; is equal to (no type conversion)

&& logical AND
|| logical OR
! logical NOT

Console.log(8*null);
returns 0                 Undefined null was auto type-converted to number 0
Console.log("5" - 1);
returns 4                 String "5" was auto type-converted to number 5
Console.log("5" + 1);
returns 51                number 1 was auto type-converted to String "1" (Concatenated)
Console.log("five" * 2)
returns NaN               String "five" was auto type-converted to undefined NaN
Console.log(false == 0)
returns true              false == 0 true == 1 false != !0 true != !1



/*
