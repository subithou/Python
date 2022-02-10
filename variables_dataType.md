[Home](https://github.com/subithou/Python) / Variables and Data Types
# Varibales and Data Types

### What is a variable?
* The variable is a named memory location which can store the data.
* Variable names are case sensitive ( num and NUM are considered as different variables ).   

 **Rules for creating a variable name** 
  * Name can be formed by using numbers, alphabets and underscore ( _ ). 
  * First letter should be an alphabet or underscore ( _ ).
  * The special characters are not allowed, except underscore ( _ ).
  * Keywords are not allowed.
  * Blank spaces are not allowed.
    
``` text
Example

Valid variable names :  

  * variable1
  * _num
  * p123
  
Invalid variable names :

  * 7name - The starting letter should be an alphabet
  * vari%#@!able - The special characters are not allowed
  * if - Keywords are not allowed
  * Sachin Tendulkar - Blank spaces are not allowed
```  
### Data Types
* The Data Type means it's the type of data we use.  
* In mathematics we can see decimal numbers, natural numbers, complex number ...etc, like this every programming languages have different data types.  
* In Python the data types care 
  * Numeric Types -   `str`
  * Text Type -       [`int`](#Integer)<a></a> [`float`](#Floating_point_Number)<a></a> [`complex`
 ](#Complex_Number)<a></a>
  * Sequence Types -  `list` `tuple` `range`
  * Mapping Type -    `dict`
  * Set Types -       `set` `frozenset`
  * Boolean Type -    `bool`
  * Binary Types -    `bytes` `bytearray` `memoryview`

## Numeric Types
In Numeric Data Types contains 
* [Integers](#Integer)<a name="Integer"></a>
* [Floating point Number](#Floating_point_Number)<a name="Floating_point_Number"></a>
* [Complex Number](#Complex_Number)<a name="Complex_Number"></a>

### Integer 
* Int or Integer which can be a whole numbers, positive and negative numbers.
* It doesn't contain decimals.
```
Example for Integers :

10
20
-56
5968745568
```

### Floating point Number
* float or Floating point Number whih can be positive and negative numbers with decimals.
* Also it can be represent using **e** or **E**, which indicate the power of 10.
```
Example for Floating point number :

10.56
20.15
-53.069875
25e3
-5632e4
```

### Complex Number
* Complex numbers are in the form of **a + bj**
* **a** is real part,**bj** is imaginary part and **a&b** are constants
```
Example for Complex Numbers :

10+20j
-20j
10j
```
