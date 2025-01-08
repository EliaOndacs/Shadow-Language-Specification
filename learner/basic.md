# The Basics

before we get started on this tutorial
all codes shown in this tutorial are made for the official interpreter implementation
and may not work on other implementation

## Hello, World!

arguably the first program that any programmer runs is a simple `hello, world!` program
so lets start from there:

```ShadeLang

print("hello, world!")
```

running this program by the interpreter
will show a text in your terminal that says 'hello, world!'.
if this is incorrect and your not using the official implementation
please check with the maintainers of the implementation your using and report a bug

## Variables

in Shadow variables are defined like this:

```ShadeLang

$x = 2
```

which it will set the variable of name `x` to the value of integer `2`

after a variable creation, it value can be changed
using the same syntax.

## If Conditions

the syntax for a simple if-condition that checks for the value of a variable is
as follows:

```ShadeLang

$x = 2
if ($x == 2) {
    print("variable x equals to 2!")
}
```

in this case it will result in the print function being called
and the text to be printed to the console

but sometimes we want to check for otherwise
the syntax is as following:

```ShadeLang

$x = 2
if ($x == 3) {
    print("variable x equals to 3!")
} else {
    print("variable x does not equal to 3!")
}
```

in this case, since variable `x` was not equals to `3`, it executed the else block

## Next Up

next chapter: [control-flows](control_flow.md)
