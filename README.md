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