#C Practice
'''
1. Concatnate Two Strings without using the inbuilt library functions and only using the while loop.

#include<stdio.h>
int main()
{
  char a[] = "Hello";
  char b[] = "World";
  int i = 0;
  int j = 0;
  while(a[i]!='\0')
  {
    i=i+1;
  }
  while(b[j]!='\0')
  {
    a[i]=b[j];
    i++;
    j++;
  }
  a[i]='\0';
  printf("%s",a);

}

'''
