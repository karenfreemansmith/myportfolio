# Java Notes

## Reserved Words:
Reserved words for Java cannot be used as variable or class names. Some are not being used in Java (const & goto) but are still reserved. Previous versions of Java had more reserved words which were dropped because they were not being used. Java also reserves [true](https://en.wikipedia.org/wiki/Truth_value), [false](https://en.wikipedia.org/wiki/Truth_value), and [null](https://en.wikipedia.org/wiki/Null_pointer).

| | | | | |
|---------|----------|------------|-----------|--------------|
| [absract](https://en.wikipedia.org/wiki/Abstract_type) | [continue](https://en.wikipedia.org/wiki/Control_flow#Continuation_with_next_iteration) | [for](https://en.wikipedia.org/wiki/For_loop) | [new](https://en.wikipedia.org/wiki/Object_lifetime#Java) | [switch](https://en.wikipedia.org/wiki/Switch_statement) |
| [assert](https://en.wikipedia.org/wiki/Assertion) | [default](https://en.wikipedia.org/wiki/Switch_statement) | [goto](https://en.wikipedia.org/wiki/Goto) | [package](https://en.wikipedia.org/wiki/Java_package) | [synchronized]() |
| [boolean](https://en.wikipedia.org/wiki/Boolean_data_type) | [do](https://en.wikipedia.org/wiki/Do_while_loop) | [if](https://en.wikipedia.org/wiki/Conditional) | [private](https://en.wikibooks.org/wiki/Java_Programming/Classes,_Objects_and_Types) | [this](https://en.wikipedia.org/wiki/This) |
| [break](https://en.wikipedia.org/wiki/Switch_statement) | [double](https://en.wikipedia.org/wiki/Double_precision) | [implements]() | [protected](https://en.wikibooks.org/wiki/Java_Programming/Classes,_Objects_and_Types) | [throw](https://en.wikipedia.org/wiki/Exception_handling_syntax#Java) |
| [byte](https://en.wikipedia.org/wiki/Byte) | [else](https://en.wikipedia.org/wiki/Conditional) | [import]() | [public](https://en.wikibooks.org/wiki/Java_Programming/Classes,_Objects_and_Types) | [throws](https://en.wikipedia.org/wiki/Exception_handling_syntax#Java) |
| [case](https://en.wikipedia.org/wiki/Switch_statement) | [enum](https://en.wikipedia.org/wiki/Enumerated_type) | [instanceof]() | [return](https://en.wikipedia.org/wiki/Method) | [transient](https://en.wikipedia.org/wiki/Transient) |
| [catch](https://en.wikipedia.org/wiki/Exception_handling_syntax) | [extends](https://en.wikipedia.org/wiki/Inheritance) | [int](https://en.wikipedia.org/wiki/Integer) | [short](https://en.wikipedia.org/wiki/Integer) | [try](https://en.wikipedia.org/wiki/Exception_handling_syntax#Java) |
| [char](https://en.wikipedia.org/wiki/Character) | [final](https://en.wikipedia.org/wiki/Final) | [interface](https://en.wikipedia.org/wiki/Interface) | [static](https://en.wikipedia.org/wiki/Static_variable) | [void](https://en.wikipedia.org/wiki/Void_type) |
| [class](https://en.wikipedia.org/wiki/Class) | [finally](https://en.wikipedia.org/wiki/Exception_handling_syntax#Java) | [long](https://en.wikipedia.org/wiki/Integer) | [strictfp](https://en.wikipedia.org/wiki/Strictfp) | [volatile](https://en.wikipedia.org/wiki/Volatile) |
| [const](https://en.wikipedia.org/wiki/Constant) | [float](https://en.wikipedia.org/wiki/Single-precision_floating-point_format) | [native](https://en.wikipedia.org/wiki/Java_Native_Interface) | [super](https://en.wikipedia.org/wiki/Inheritance) | [while](https://en.wikipedia.org/wiki/Do_while_loop) |

## Variables & Data Types
### Primitive (or simple) Types
boolean, char, byte, short, int, long, float, double

## Conditional Statements
* if(*condition*) {

  } else {

  }
* switch(*value*)
    case:
      break;
    default:

## Looping
* for() {}
* while(*condition*) {}
* do {} while(*condition*)

## Classes & Objects
* public = available to all
* protected = available within package
* private = only available within current code block
* static
* void = doesn't return anything
