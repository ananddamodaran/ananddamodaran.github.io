---
layout: post
title: C Programs
excerpt: "Getting started with C programming."
categories: [C]
comments: true
url : https://anand.dev/articles/2022-05/how-to-install-java-in-ubuntu
identifier: 1234
image:
  feature: https://miro.medium.com/max/8512/0*-hMqapazeDO-IOck
  credit: Medium
  creditlink: 
---

### 1. Print your name

<div align="center">
    <embed src="https://www.mermaidchart.com/raw/c89a4b03-a5e4-42b3-84ca-3ceef18244f6?version=v0.1&theme=retro&format=svg" width="500" height="300"  type="image/svg+xml" />
</div>

``` c
/* Program No: 01
* Aim: Print your name */

#include <stdio.h>

int main() {
   printf("Anand Damodaran\n");
}
```

### 2. Find the sum of two integers

<div align="center">



<div align="center">
    <embed src="https://www.mermaidchart.com/raw/a40b31a3-96c4-492a-87b0-46ff0b6032ec?version=v0.1&theme=retro&format=svg " width="500" height="500"  type="image/svg+xml" />
</div>
 

</div>

``` c
/* Program No: 02
 * Aim: Find the sum of two integers */

#include <stdio.h>

int main() {
 int firstNumber, secondNumber, sum;

 firstNumber = 10;
 secondNumber = 20;
 sum = firstNumber + secondNumber;

 printf("Sum of two numbers: %d", sum);
}

```

### 3. Find the product of two real numbers



<div align="center">
    <embed src="https://www.mermaidchart.com/raw/2c801b9d-33cc-48b8-a1c4-c7adbb73a0a9?version=v0.1&theme=retro&format=svg" width="500" height="500"  type="image/svg+xml" />
</div>



``` c
/* Program no: 03
 * Aim: Find the product of two real numbers
 */
#include <stdio.h>

int main() {
  float firstNumber, secondNumber, product;
  
  firstNumber = 100;
  secondNumber = 200;
  product = firstNumber * secondNumber;

  printf("Product of two real numbers: %f", product);
}

```