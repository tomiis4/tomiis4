# <a href="#">Language</a> Cheatsheet <img width="50em" src="#">

<table>
<td>

* [File](#file)
* [Hello world](#hello-world)
* [Importing packages](#importing-packages)
* [Variables & Types](#variables)
	* [structs](#structs)
	* [map](#map)
* [Functions](#functions)
* [Logic statements](#logic-statements)
	* [if/else](#ifelse)
	* [switch/case](#switchcase)

</td>
<td>

* [Loop](#loop)
	* [for-i](#for-i)
	* [for-in](#for-in)
	* [while](#while)
* [Converting](#converting)
* [Build-in iunctions](#build-in-functions)
	* [func](#func)

</td>
<td>

* [Pointers](#pointers)
* [Unit testing](#unit-testing)
* [External file](#external-file)

</td>
<td>

* [Remote packages](#remote-packages)
* [Packages](#packages)
	* [pkg](#pkg)
* [Project ideas](#project-ideas)
</td>
</table>


## File

### Run file
`lang-name run file.lang-name`

### Generate exe file
`lang-name build file.lang-name`

## Hello world
```lang-name

```


## Importing packages
```lang-name

```


## Variables
```lang-name
// automatic type
foo := "String"
slice := []<type>{}

// constants
const var <type> = <value>

// set own type
var <name> <type> = <value>
var slice = []<type>{}

// arrays
array := [...]<type>{} // fixed size
array := [][]<type>{} // 2D array

// maps (similar to objects/json in JavaScript)
maps := map[<key-type>]<value-type>{}

/*
Type: 
	bool              = %t = true, false
	int8, 16, 32, 64  = %d = number in range of x bits, can be negative
	uint8, 16, 32, 64 = %d = number in range of x bits, can't be negative
	float32, 64       = %g = decimal numbers
	string            = %s = string
*/
```

### Structs
```lang-name
```

### Map
```lang-name

```


## Functions
```lang-name
func name() {
	//...
}

// return
func name() <type> { return x }
func name() (<type>, <type>) { return x, y }

// parameters 
func name(param1 <type>) {  }
func name(param1, param2 <type>) {  } // if param1 have same type as param2
```


## Logic Statements

### If/else
```lang-name

```

### Switch/case
```lang-name

```


## Loop

### For-I
```lang-name

```

### For-In
```lang-name
```

### While
```lang-name

```


## Converting
```lang-name

```


## Build-In Functions

### func
```lang-name
```

## Pointers
```lang-name

```


## Unit Testing
```sh
```
```lang-name
// main.lang-name
// main_test.lang-name
```


## External file
```lang-name
// folder structure
|- main.lang-name
|
|- example
  |- second.lang-name

// main.lang-name


// second.lang-name

```



## Remote packages

### Install packages
```

```

### Import packages
```lang-name
```


## Packages

### pkg

```lang-name
// code
```


## Project ideas
* [name](link)
