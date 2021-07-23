Variables in Jelly are mutable (meaning their value can be edited). When you create a variable, it can be used in the input of functions needing a variable. You can also set them to new values using the same syntax you use to set them in the first place. To set a variable there are a few different options, `Strings`,  `Numbers`, `Magic Variables`, and `Global Variables`. 

## Variable with a String value
If you want to declare a variable with the value of a string, you can use the following syntax

```
var HelloWorld = "Hello World"
```

This will automatically be converted into the following Shortcuts actions
- Text: Hello World
- Variable: Linking to the text action

## Variable with a Number value
If you want to declare a variable with the value of a number, you can use the following syntax

```
var MeaningOfLife = 42
```

This will automatically be converted into the following Shortcuts actions
- Number: 42
- Variable: Linking to the text action

## Variable with a Magic Variable value
If you wish to convert a magic variable into a regular variable, you can set a variable to the value of a magic variable. Since magic variables are not mutable, this is how you will want to mutate the value you get in return of a function. To do this you can use the following syntax

```
var MyVariable = FunctionOutput
```

## Variable with a Global Variable value
Just like magic variables, global variables are not mutable. To edit them you will need to set a variable to the global variable. This can be done with the following syntax

```
var MutableGlobalVar = ShortcutInput
```