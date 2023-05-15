# Functions and Operators 

Functions are basically **Reusable Code** <br>

**function** is the keyword used for defining a function

### Syntax
```
function function_name(parameters){
    function defenition;
    return output_value
}
```

Lets understand Functions with an example

```
function numValue(){
    return 10
}
```
When the function **numValue()** is called anywhere else in the program <br>
will give the value 10

```
const value = numValue();
```
Now the variable value has the number 10 stored in it 

This value could also be strings, characters, and boolean values

## Parameters 

Lets consider a function from the following example
```
function sumofnumbers(a,b){
    const output = a + b;
    return output;
}
```
In the above example *a* and *b* are parameters of the function, <br>
Parameters could be input values or conditions that need to be set for a function.
