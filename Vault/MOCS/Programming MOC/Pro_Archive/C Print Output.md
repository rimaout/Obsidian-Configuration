---
Created: 2023-03-21
Type: Programming Note
Programming Language: "[[C MOC]]"
Related: 
Completed: false
---
---

# Printf
To output values or print text in C, you can use the `printf()` function:
``` C
#include <stdio.h>  
  
int main() {  
  printf("Hello World!");  
  return 0;  
}
```

---
# What's `\n` exactly ?
The newline character (`\n`) is called an **escape sequence**, and it forces the cursor to change its position to the beginning of the next line on the screen. This results in a new line.

More information about [[C Escaping Sequences]]

---
# How to print [[C Variables And Constants|variables]]

```c

```

## float 
**How to print a fixed digit number after the dot:**
```c 
float num = 1.234567889

printf("%f", num);   //OUTPUT: 1.23456789
printf("%f.1", num); //OUTPUT: 1.2
printf("%f.2", num); //OUTPUT: 1.23
printf("%f.3", num); //OUTPUT: 1.234

```