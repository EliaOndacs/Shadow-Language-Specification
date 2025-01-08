# Control Flows

in this chapter you learn about control-flows, they are really
important in the process of making a program.

## While Loops

while loops area control flow structure
that repeat a block of code until a condition is met

the syntax is as following:

```ShadeLang

// warning: loops forever!
while (true) {
    print("hello, world!")
}
```

running the following it will print `hello, world!` repeatedly forever
but the `true` can be replaced with a condition or a function call that returns a boolean

> Note:
> a boolean is a value of `true` or `false`

## for loops

for loops are really similar to while loops, but their difference is
that a for loop comes with a default variable that keep track of the state of the loop

the syntax is as following:

```ShadeLang

for ($i = 0; $i < 5; $i = $i+1) {
    print("hello, world!")
}
```

the code mentioned above, will execute the block 5 times
because of the condition we set `$i < 5`

## foreach loops

foreach loops are also similar to `for loops` and `while loops` but
they are made to iterate over an array or an indexable type

the syntax is as following:

```ShadeLang

foreach ($i : 1..5) {
    print("$i")
}
```

the code above will print the following:

```
1
2
3
4
5
```

> Note:
> the syntax `1..5` will generate an array that ranges from the value 1 to value 5

## switch statements

switch is a more powerful version of an if-condition
it allows you to match a variable against multiple expressions

the syntax is as following:

```ShadeLang

$x = 2
switch ($x) {
    case (1) {
        print("variable x equals to 1")
    }

    case (2) {
        print("variable x equals to 2")
    }

    case (3) {
        print("variable x equals to 3")
    }
}
```

in the code above the variable `$x` equals to `2`
so it will execute the respective block accordingly
