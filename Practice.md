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

```

# C Practice  -  Reverse an array using pointers.

```c


#include <stdio.h>

int main()
{
    int arr[] = {10,20,30,40};
    int *ptr = &arr[3];
    for(int i = 3;i!=-1;i--)
    {
        printf("%d ",*(ptr-i));
    }
    
    
}

