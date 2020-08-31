# Provided Code 

> A provided code is a **file** that contains a **code** which will 
>be compiled with the [submitted codes](domain/submission/submitted-code/)
> but not accessible to students.

Sometimes, a problem needs to provide some codes so that students
don't have to code them themselves, for example: a header file, a main function, 
some libraries, or even something that need to be hidden, like the encrypt key to your
test case, etc.

## Example 1

**File Name**: main.c

```
#include <stdio.h>
#include <add.h>
int main() {
    int a, b;
    scanf("%d %d", a, b);
    printf(add(a, b));
    return 0;
}
```

## Example 2

**File Name**: add.h

```
int add(int a, int b);
```




