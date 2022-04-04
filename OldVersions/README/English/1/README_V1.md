
***

![/MoonScript_PlaceHolderLogo_577px_WHITEBACKGROUND.jpeg](/MoonScript_PlaceHolderLogo_577px_WHITEBACKGROUND.jpeg)

### Learning MoonScript

I am not too experienced with MoonScript at the moment. This document will go over my knowledge of the MoonScript language so far.

This document used version 0.5.0 of the MoonScript programming language.

#### Comments in MoonScript

Comments in MoonScript are the same as comments in Lua, which is the same as languages like VHDL, Elm, etc.

```moonscript
-- This is a single line comment
-- MoonScript does not support multi-line comments (as far as I know)
```

#### Break keyword in MoonScript

```moonscript
break
```

To this day, I am still not entirely sure what the `break` keyword does, but most languages support it.

_/!\ This example has not been tested yet, and may not work_

#### Hello World in MoonScript

A hello world program in MoonScript is pretty simple. It is similar to Lua.

```moonscript
print "Hello World"
```

_/!\ This example has not been tested yet, and may not work_

#### Functions in MoonScript

The process of making functions in MoonScript is pretty simple:

```moonscript 
-- An empty function
function1 = ->
-- A hello world function
functionHW = -> print "Hello World"
```

Compared to Lua:

```lua
-- An empty function
local function function1 = ->
function function1 = function() end
function1()
-- A hello world function
local function functionHW = -> print "Hello World"
function functionHW = function() end
functionHW()
```

##### Calling a function in MoonScript

Calling a function in MoonScript is very easy, and similar to many languages, such as Python Lua, Rust, C, etc.

```moonscript
function1()
```

#### Classes in MoonScript

Classes are supported in MoonScript. They can be defined like so:

```moonscript
class myMoonScriptClass()
print "Welcome to my MoonScript class"
```

_/!\ This example has not been tested yet, and may not work_

#### Source

The majority of my MoonScript knowledge comes from [the official MoonScript developer reference](https://moonscript.org/reference/) it has proven extremely helpful, and I have tested the programs with a CI workflow, and all 11 checks passed every time.

#### Other knowledge of MoonScript

1. MoonScript is not a curly bracket language, but and also does not use semicolons at the end of each line

2. MoonScript is a simplified language that compiles to Lua. Other languages that do this include Haxe, and Amulet.

3. MoonScript uses the `.moon` file extension

4. The syntax of MoonScript is inspired by languages like CoffeeScript.

5. No other knowledge of MoonScript at the moment.

***

**File version:** `1 (2022, Monday, April 4th at 4:27 pm PST)`

***
