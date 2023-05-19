# String Manipulation

## Index 

In JavaScript the index of characters in a string starts from 0. This is known as **Zero-Based Indexing**

## Extracting Characters from a String

To extract a character from a string there are two ways 

1. Using the **charAt** function

**Syntax**
```
string.charAt(index);
```

2. Using **[]** 

**Syntax**
```
string.[index];
```

## Character Casing

To change the case of the character to Upper or Lower case there are functions in JavaScript

1. toLowerCase()

This changes the case of the string or character to lower case

**Syntax**
```
string.toLowerCase()
```

2. toUpperCase()

This changes the case of the string or character to upper case

**Syntax**
```
string.toUpperCase()
```

## String Length

We can use the **length** function in JavaScript to find the length of the string 

Length of a character is 1

**Syntax**
```
string.length;
```
The output of this can be either printed using console.log or can be stored into a new variable 

## Finding the Index

In JavaScript we can find the index of a certain character or string in a string using the **indexOf** function

**Syntax**
```
string.indexOf("character"); //to find the index of a character in a string
string.indexOf("string"); //to find the index of a string within a sentence
```
If a string or a character is not found then the function returns a **-1**

This function gives the index of the first character it encounters

The **lastIndexof()** function gives the last encountered character

## String Slicing