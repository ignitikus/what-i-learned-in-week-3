# What I Learned In Week 3

## *Variables*
Can be imagined as virtual containers.
Variables can be declared by using certain keywords:
  * `let` - Declares variable that can be reassigned on a line below;
  * `const` - Preferred keyword for declaration. Declares variable that cannot be reassigned;
  * `var` -  Outdated keyword. Almost the same functionality as `let`.
---
### *For example:*

    let x = 5;
    x = 4;
### We declared `x` as 5 using `let` keyword. On the line below we've changed the value of `x` to 4; 

    const x = 6;
### This time we used `const` to declare `x`. This variable cannot be re-declared without changing the original value.

## *Data types*
Variables can hold different type of data:

    Numbers: 1,2,3 etc.
    String: "Hello world!"
    Boolean: True or False
    Null: No value
    Undefined: A variable that was assigned but not defined


## *Functions*
Function is a block of code written for a particular task.

    function addsOne(x){
    return x = x + 1;
    }
We use keyword `function` to declare it. Then we assign name using `camelCase`. In parenthesis we input parameters. In this case we used `x` followed by curly brackets. Within curly brackets we determine commands that will be executed upon calling of this function. 

To call a function use the name of the function with arguments within parenthesis:

    addsOne(2);

The output will be `return`ed as 3. 