---
title: Data Types of JavaScript
author: Achyuta Pataki
date: 2020-12-31 00:00:00 +530
categories: [Javascript, Frontend language]
tags: [data-types,booleans,strings,number]
math: true
pin: false
---
<style>
table, th, td {
  border: 1px solid black;
}
</style>
Hello there welcome to my Javascript tutorial, today we are talking about Data types of javascript.There are 5 basic data types in js(Javascript).
Those are `numbers`, `booleans`, `objects`, `arrays`, `strings `.

### Variables
Variables of js are same like variables in math.They can change.
```js
let age  = 20 ;
```
All variables should declared using the key word `let` like `let a="rohit";`.First the keyword `var` is used for declaring the variables.
All data types are declared from `let` keyword.
## Data Types
### Numbers
Numbers can be decimal or non decimal.You can do operations on them using there variable.
#### Table contaning oparators of javascript
<table>
  <tr>
    <th>Operator</th>
    <th>Description</th>
  </tr>
  <tr>
    <td>+</td>
    <td>Addition</td>
  </tr>
  <tr>
    <td>-</td>
    <td>Subtraction</td>
  </tr>
  <tr>
    <td>*</td>
    <td>Multiplication</td>
  </tr>
  <tr>
    <td>**</td>
    <td>Exponentiation</td>
  </tr><tr>
    <td>/</td>
    <td>Division</td>
  </tr><tr>
    <td>%</td>
    <td>Modulus (Remainder)</td>
  </tr><tr>
    <td>++</td>
    <td>Increment</td>
  </tr><tr>
    <td>--</td>
    <td>Decrement</td>
  </tr>
</table>

### Strings
Strings can be defined in double cotes (`""`) or single(`''`).
If you try for for:
``` js 
let a = 20;
let b = 'he'
let c = a + b;
```
Then the answer will be `20he`.What? Yes thats right Js engin treats the variable a as a string and concatnate them.

### Booleans
Booleans have only two values `true` and `false`.Only two no more.
if you think like a variable `a = 20 and b = 20` if you write `c = a == b` then the value would be `true` a boolean value.

