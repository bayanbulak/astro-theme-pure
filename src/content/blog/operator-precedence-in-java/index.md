---
title: Operator Precedence in Java
publishDate: 2024-03-09
description: 'operator precedence in Java'
tags:
  - Java
heroImage: { src: './thumbnail.jpg', color: '#64574D' }
language: 'English'
---

## Operator Precedence in Java

| Level  | Operator                                               | Description                                                  | Associativity |
| ------ | ------------------------------------------------------ | ------------------------------------------------------------ | ------------- |
| **16** | `()`<br>`[]`<br>`new`<br>`.`<br>`::`| parentheses <br> array access<br> object creation<br>member access<br>method reference | left-to-right |
| **15** | `++`<br> `--`| unary post-increment <br> unary post-decrement                    | left-to-right |
| **14** | `+` <br>`-`<br> `!` <br>`~`<br> `++`<br> `--` | unary plus<br> unary minus<br> unary logical NOT<br> unary bitwise NOT<br> unary pre-increment<br> unary pre-decrement | right-to-left |
| **13** | `()`                                             | cast                                        | right-to-left |
| **12** | `*` `/` `%`                                                | multiplicative                                               | left-to-right |
| **11** | `+ -`<br> `+`                                              | additive<br> string concatenation                                | left-to-right |
| **10** | `<< >>`<br> `>>>`                                          | shift                                                        | left-to-right |
| **9**  | `< <=`<br> `> >=`<br> `instanceof`                             | relational                                                   | left-to-right |
| **8**  | `==` <br>`!=`                                              | equality                                                     | left-to-right |
| **7**  | `&`                                                    | bitwise AND                                                  | left-to-right |
| **6**  | `^`                                                    | bitwise XOR                                                  | left-to-right |
| **5**  | `\|`                                                    | bitwise OR                                                   | left-to-right |
| **4**  | `&&`                                                   | logical AND                                                  | left-to-right |
| **3**  | `\|\|`                                                   | logical OR                                                   | left-to-right |
| **2**  | `?:`                                                   | ternary                                                      | right-to-left |
| **1**  |`=` `+=` `-=`<br> `*=` `/=` `%=`<br> `&=` `^=` `\|=`<br> `<<=` `>>=` `>>>=` | assignment                                                   | right-to-left |
| **0**  | `->`<br>`->`                                                   | lambda expression<br>switch expression| right-to-left |

## See Also

* [Operator Precedence in Java, princeton](https://introcs.cs.princeton.edu/java/11precedence/)
