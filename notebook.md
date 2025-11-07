# My notebook

## Table of Contents
- [Code Definitions](#code_definitions)
- [what is flutter?] #what-is-fluuter}
- [key terms and defintions] {#key-terms-and-definitions}
- [layout and design widgets] {layout-and-design-widgets}
- [definitions with structures] {#flutter-definitions}
- [code definitions] {#code-definitions}
- [notebook style guide]{#markdown-style-guide-for-coding-notebook}

## Flutter Notes

### What is Flutter?
- Definition:
- Why is it useful?

---1

### Key Terms and Definitions

| Term             | Definition                                      | Example / Notes                          |
|------------------|--------------------------------------------------|-------------------------------------------|
| Widget           |                                                  |                                           |
| MaterialApp      |                                                  |                                           |
| Scaffold         |                                                  |                                           |
| StatelessWidget  |                                                  |                                           |
| StatefulWidget   |                                                  |                                           |
| Navigator        |                                                  |                                           |
| AppBar           |                                                  |                                           |
| Column           |                                                  |                                           |
| Row              |                                                  |                                           |
| Container        |                                                  |                                           |
| Text             |                                                  |                                           |
| Image.network    |                                                  |                                           |
| Padding          |                                                  |                                           |
| Center           |                                                  |                                           |

 

 

 







| Term | Definition | Base Structure / Syntax | Real Life Example | App Example |
|------|------------|--------------------------|-------------------|-------------|
|      | A named container used to store a value that may change. | `var x = 5;` |  |  |
|      | A fixed value that cannot change once set. | `const PI = 3.14;` |  |  |
|      | The kind of value a variable holds, like numbers or text. | `int`, `String`, `bool` |  |  |  
|      | A sequence of characters used to represent words or text. | `"Hello World"` |  |  |
|      | Whole number values. | `int age = 16;` |  |  |
|      | Number values with decimals. | `double age = 16.2;` |  |  |
|      | A value that can be true or false. | `bool isLoggedIn = false;` |  |  |
|      | A collection of values in a specific order. | `List<String> names = [];` |  |  |
|      | A special value that means “nothing.” | `String? name = null;` |  |  |
|      | A reusable block of code that performs an action. | `void sayHi() { print("Hi"); }` |  | |
|      | The information passed into a function to change how it works. | `greet(String name)` |  |  |
|      | The result a function gives back. | `return total;` |  |  |
|      | Where a variable or function can be used. | (No set syntax — concept-based) |  |  |
|      | Blueprint for creating objects with specific structure and behavior. | `class Dog {}` |  |  |
|      | A specific version of a class. | `Dog myDog = Dog();` |  |  |
|      | A variable that belongs to a class/object. | `String name;` |  |  
|      | A function that belongs to a class. | `void bark() {}` |  |  |
|      | A special function used to set up a class when it’s created. | `Dog(this.name);` |  |  |
|      | Hiding the inner workings of code so users only interact with what they need. | (Concept — not specific code) |  |  |
|      | Changing how a built-in or inherited function behaves. | `@override` |  |  |
|      | A function that does not return a value. | `void printMessage() {}` |  |  |





## Flutter Definitions

| Term | Definition and Description | Base Structure | Real Life Example | App Example |

|------|----------------------------|----------------|-------------------|-------------|
|      | A function that runs when your app starts. It tells Flutter what app to show. | `void main() => runApp(MyApp());` |  |  |
|      | The widget that sets up your whole app’s look and navigation. | `MaterialApp(...)` |  |  |      | A widget that gives you the basic layout: background, navigation bar, floating button, etc. | `Scaffold(...)` |  |
|      | A widget that holds and displays your content in a straight line from top to bottom. | `Column(...)` |  |  |
|      | A widget that shows things side-by-side. | `Row(...)` |  |  |
|      | A box that holds other widgets. You can add color, padding, borders, or size. | `Container(...)` |  |  |
|      | A widget to display text on the screen. | `Text('Hello')` |  |  |
|      | A widget to show an image using a link from the internet. | `Image.network('https://...')` |  |  |
|      | A clickable button that floats above content. You choose what happens when it's clicked  `ElevatedButton(onPressed: ..., child: ...)` |  |  |
|      | The code that gets run when a button is tapped or something happens. | `onPressed: () => doSomething()` |  |  |
|      | A class that creates widgets that never change. Good for static screens. | `class HomeScreen extends StatelessWidget` |  |  |
|      | A class for widgets that can change while the app is running. | `class MyWidget extends StatefulWidget` |  |  |
|      | Lets you move from one screen to another using route names. | `Navigator.pushNamed(context, '/about')` |  |  |

|      | Makes space around a widget inside its container. | `Padding(padding: EdgeInsets.all(.0), child: ...)` |  |  |
|      | Aligns content in the center of the screen or container. | `Center(child: ...)` |  |  
|      | Automatically puts widgets onto a new line when there's no space. | `Wrap(children: [...])` |  |  |
|      | This marks a method as one that’s replacing a method in a parent class. | `@override` |  |  |
|      | The special fnction in every widget that describes what gets drawn on the screen. | `Widget build(BuildConcontext) {...}` |  |  |
|      | Required in every widget class to describe what to show. | `build` |  |  |
|     | A variable that helps the widget know where it is and lets it communicate with the app. | `BuildContext context` |  | |      | A keyword used to pass a value to the parent widget. | `super.key` |  |  |
|      | A keyword that means the value won't change and is set once. | `const` |  |  |















| Term | Definition | Base Structure / Syntax | Real Life Example | App Example |

|------|------------|--------------------------|-------------------|-------------|
|      | A named container used to store a value that may change. | `var x = 5;`   |  |
|      | A fixed value that cannot change once set. | `const PI = 3.14;` |  |  
|      | The kind of value a variable holds, like numbers or text. | `int`, `String`, `bool` |  |  |
|      | A sequence of characters used to represent words or text. | `"Hello World"` |  | 
|      | Whole number values. | `int age = 16;` |  |  
|      | Number values with decimals. | `double age =16.2;` |  |  |
|      | A value that can be true or false. | `bool isLoggedIn = flse;` |  |  |
|      | A collection of values in a specific order. | `List<Strig> names = [];` |  |  |
|      | A special value that means “nothing.” | `String? name = null;` |  | 
|      | A reusable block of code that performs an action. | `void sayHi() { print("Hi"); }` |  |  
|      | The information passed into a function to change how it works. | `greet(String name)` |    |
|      | The result a function gives back. | `return total;` |  |  |
|      | Where a variable or function can be used. | (No set syntax — concept-based) |  |  
|      | Blueprint for creating objects with specific structure and behavior. | `class Dog{}` |  |  |
|      | A specific version of a class. | `Dog myDog = Dog();` |  |  |
|      | A variable that belongs to a class/object. | `String name;` |  |  |
|      | A function that belongs to a class. | `void bark() {}` |  |  |
|      | A special function used to set up a class when it’s created. | `Dog(this.name);` |  |  |
|      | Hiding the inner workings of code so users only interact with what they need. | (Concep — not specific code) |  |  |
|      | Changing how a built-in or inherited function behaves. | `@override` |  |  |
|      | A function that does not return a value. | `void printMessage() {}` |  |  |

| | | |

Scanner | Creates a scanner object to take input from user | Scanner in = new Scanner (System.in); | | import Scanner | Gives access to Scanner class, required at top | import java.util. Scanner; TIl print line statement | prints what's in the parenthesis, adds line after | System.out.printIn(" "); | | print statement | prints the content in the parenthesis | System.out.print(" "); 111 input nextline | reads in a String from the user | input. nextLine(); ||| input nextInt | reads in an int from the user | input.nextInt); | | input nextDouble | reads in a double (decimal) from the user | input. nextDouble); l input nextBoolean | reads in a boolean (true/false) from the user | input. nextBoolean (); ||| Arithmetic operators | - % (modulus, returns the remainder from dividing) | | Compound operators (applies the result to the variable) | += / = %= ++ (adds 1)



| Maximum int | The max value an int can hold: 2147483647 |
Integer. MAX_VALUE | | | | Minimum int |
The minimum value an int can hold: -2147483648 |
Integer.MIN_VALUE | | | integer overflow |
Integer.MAX_VALUE + 1 == MIN_VALUE, it wraps around | | |
| Integer underflow Integer.MIN_VALUE-1 == MAX_VALUE, it wraps around|
| round-off error | an approx. of the actual value, result is rounded to the nearest value that fits within the available bits




round-off error | an approx. of the actual value, result is rounded to the nearest value that fits within the available bits I I Overloaded method/function or constructor | Uses the same name, but has different parameters | Pizza(), Pizza(String toppings) 2












