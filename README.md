# golang-step2step

  

## Hands-on exercise #1

### Using the short declaration operator, ASSIGN these VALUES to VARIABLES with the IDENTIFIERS “x” and “y” and “z”

  

https://play.golang.org/p/FDvKIR4Oudj

  

## Hands-on exercise #2

### Use var to DECLARE three VARIABLES. The variables should have package level scope. Do not assign VALUES to the variables. Use the following IDENTIFIERS for the variables and make sure the variables are of the following TYPE (meaning they can store VALUES of that TYPE).

* identifier “x” type int

* identifier “y” type string

* identifier “z” type bool

https://play.golang.org/p/A6S1em2paDD

## Hands-on exercise #3

Using the code from the previous exercise,

 -  At the package level scope, assign the following values to the three variables
	 - for x assign 42
	 - for y assign “James Bond”
	 - for z assign true
    
- in func main
	- use fmt.Sprintf to print all of the VALUES to one single string. ASSIGN the returned value of TYPE string using the short declaration operator to a VARIABLE with the IDENTIFIER “s”
	- print out the value stored by variable “s”

https://play.golang.org/p/i0Z0sl-dUrn


## Hands-on exercise #4

-   FYI - nice documentation and new terminology “underlying type”
    
-   [https://golang.org/ref/spec#Types](https://golang.org/ref/spec#Types)
    
For this exercise

1.  Create your own type. Have the underlying type be an int.
2.  create a VARIABLE of your new TYPE with the IDENTIFIER “x” using the “VAR” keyword
3.  in func main
	4. print out the value of the variable “x”
	5. print out the type of the variable “x”
	6. assign 42 to the VARIABLE “x” using the “=” OPERATOR
	7. print out the value of the variable “x”

https://play.golang.org/p/H65-ebgQsII


## Hands-on exercise #5

Building on the code from the previous example

1.  at the package level scope, using the “var” keyword, create a VARIABLE with the IDENTIFIER “y”. The variable should be of the UNDERLYING TYPE of your custom TYPE “x”
   
1.  eg: 

![](https://lh3.googleusercontent.com/J4M2ayZRF4TDQG6nKJKSP4Rcgqiv_Q4ZmRRLunYJfkvuZDqprc5ftHkpGNIOsHNXUkDucQ9mGAq-i9IU7Qr6r3V1l8k3erZHdGiq7TEKU5uzYkh-JGR3edSVecFB2IAVOUBpAy-K)

2.  in func main
	3. this should already be done
		4. print out the value of the variable “x”
		5. print out the type of the variable “x”
		6. assign your own VALUE to the VARIABLE “x” using the “=” OPERATOR
		7. print out the value of the variable “x”
	4. now do this
		5. now use CONVERSION to convert the TYPE of the VALUE stored in “x” to the UNDERLYING TYPE
			6. then use the “=” operator to ASSIGN that value to “y”
			7. print out the value stored in “y”
			8. print out the type of “y”
    
https://play.golang.org/p/Mmq6FMYa2f3


