# C Practice

```c
#include <stdio.h>

int main() {
  char a[20] = "Hello"; // Increased size to accommodate concatenated string
  char b[] = "World";
  int i = 0;
  int j = 0;

  // Find the end of string 'a'
  while (a[i] != '\0') {
    i++;
  }

  // Concatenate string 'b' to string 'a'
  while (b[j] != '\0') {
    a[i] = b[j];
    i++;
    j++;
  }

  // Null-terminate the concatenated string
  a[i] = '\0';

  printf("%s", a);

  return 0;
}
