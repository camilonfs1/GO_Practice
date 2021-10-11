# GO

1. Go includes garbage collection

2. Go is Object-Oriented

3. Go does not use the term class

4. Go uses structs with associated methods


# Concurrency

Moore's Law used to help performance, it basically says, that the number of transistors on a chip boubles every 18 months.

Concurrency is the managemen of multiple tasks at the same time. When i say at the same time, they might not actually be executing at the same time. Maybe they are excuting on a single core processor.

Concurrent programming it enables parallelism.

Go has a lot of concurrency primitives built-in to the language and implemented efficiently. Go routines, each one of thise Go routines represents a concurrent tasks, basically a thread

# Workspaces

It's basically a directory where your Go stuff will go, so your Go files. Typically, there's a actually a hierarchy of directories within
your workspace where you will store the different types of Go files that you're working with.

Three subdirectories: 

### 1. src - Contains source code files
### 2. pkg - Contains packges (libraries)
### 3. bin - Contains executables


## Import packages

![iamge](https://github.com/camilonfs1/GO_Practice/blob/main/src/Screenshot%20from%202021-10-09%2012-21-07.png)

Ther emust be one package calle main

# Variables

1. Must have a name and a type
2. All variables must have declarations

> var x int

> var x, y int

## Types

1. Integer (+, -, *, ...)
2. Floating point
3. Strings 

## Type Declartions

>type Clesius float64

>type IDnum int

## Initializing Variables

> var x int = 100

> var x = 100

> var x int ----> x=100

> var x int // x = 0 

## Short Variable Declaration

> x := 100

# Pointers

A pointer is an address to some data in memory. Tips give virtual address but that doesn't matter to us too much right now. So, with Pointers, there are two main operators that are associated with Pointers. The ampersand operator right there, that returns the address of the variable or the function, whatever the name is referring to, and the star operator which dereferencing, does the opposite of the ampersand. It returns the data at the address.

> & operator returns the address of a variable/function

> (*) operator retuns data at an address (dereferncing)


```go
var x int = 1
var y int
var ip *int // ip is pointer to int

ip = &x    // ip now points to x
y = *ip    // y is now 1
```

> new ( ) function creates a variable and returns a pointer to the variable

```go
ptr := new (int)
*ptr = 3
```

# Variable Scope

The places in code where a variable can be accessed

# Blocks 

A sequence of declarations and statements within matching breackets, { }

> Including functions definitions

# Lexical Scoping

Go is lexicallly scoped using blocks