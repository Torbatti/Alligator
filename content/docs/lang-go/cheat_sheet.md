+++
title = "Cheat Sheet"
description = ""
date = 2021-05-01T08:00:00+00:00
updated = 2021-05-01T08:00:00+00:00
draft = false
weight = 1
sort_by = "weight"
template = "docs/page.html"

[extra]
lead = 'AdiDoks is a Zola theme helping you build modern documentation websites, which is a port of the Hugo theme <a href="https://github.com/h-enk/doks">Doks</a> for Zola.'
toc = true
top = false
+++
## About Go
```go
// Go is Strong And Staticly Typed Language
    //that means you cant change a variable type once you decclared it
```
## Variable
```go 
// Declare , Assign later
var i int 
i = 19
```
```go 
// Declare and Assign at the same time
var i int = 19
```
```go 
// Declare and Assign at the same time
// let the compiler figure it out
i := 19
```
```go
// Var Blocks
var(
    name_1 := "Arya"
    age_1 := 19
)

var(
    name_2 := "Arash"
    age_2 := 18
)
```
```go
// Cant reDeclare variables
    var i int = 12
    // var i int = 32 // Cant Declare Variable twice in the same scope
// Can Shadow them
    var j float32 = 12.4
    {
        var j int = 22 // shadowing "j" variable
    }
```

### Scope
> TODO

### Shadowing
> TODO

### Visibility
```
Lower Case -> Package scope
Upper Case -> Export globaly
```

### Naming Conventions
> TODO

### Type Convertions
> TODO

## Constant
```go
//constant value must 
const myConst int = 25
```


## Basic Data types
### Boolean Type
```go
var defaultBool bool // boolean in go defaults to false / 0
myBool := true
yourBool := 1==2 // false
```
### Numeric Types
#### signed integer

#### unsigned integer

#### byte

### Text Types
#### Char

#### String

## Operators
### Logical
### Numeric