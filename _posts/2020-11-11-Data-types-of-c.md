---
title: Data types of C
author: Achyuta Pataki
date: 2020-12-26 13:22:00 +0530
categories: [C-programing, Programming Languages]
tags: [basic-c,data-types]
math: true
pin: true
---

Hello there I am Achyuta, today we are talking about **C programing language**. This is the first part of *c*.

## What should we learn?
<pre>
* Preprosser Directive of C.
* Data types of C.
</pre>

## Let's start...
`C`, c is the basic programing language.This is a example of c program.
Create a file ending with `.c` that will be your c file.

``` c
# include <stdio.h>
int main(int argc, char const *argv[])
{
	int c=100;
	int m=0;
	while (c>=m){
		printf("%d\n",m);
		m++;
	}
}
```

Copy the example above and run it from the instructions given below.  
* Run this command `cc (your file name).c`.  
* Run `a.out`.  

**If you are in any editor you can follow these instructions or find how to run it that should be easy.**  

## Preprosser Directive of C
Preprosser Directive of C is  
``` c
# include <stdio.h>
main()
{

}
```
## Explanation 
`# include <stdio.h>` :  
`# include` includes the given library in `<>`.You can include infinite librarys.But one after one.  
`stdio.h` is a library of c.The full form is `standrd input output`.  
`main()` is a starting point of your program.It is a function we talk about more on functionns in other blogs.  
The code in `{}` is executed.  


## Data types of C

The first data type of c is `char`. Char can hold 

