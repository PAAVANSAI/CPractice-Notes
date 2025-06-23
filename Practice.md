# C Practice  -  Concat two strings without the library functions.

```c

#include <stdio.h>

int main() {
  char a[20] = "Hello"; 
  char b[] = "World";
  int i = 0;
  int j = 0;

  while (a[i] != '\0') {
    i++;
  }


  while (b[j] != '\0') {
    a[i] = b[j];
    i++;
    j++;
  }

  a[i] = '\0';

  printf("%s", a);

  return 0;
}
