# Basic-C
#include<stdio.h>
int main()
{
  printf("Rachana Elavarapu");
  return 0;
}
# Variables
#include <stdio.h>
int main()
{
    int var1=3
    printf("%d", var1);
    return 0;
}

# multiple variables
#include <stdio.h>

int main()
{
    int var1,var2,var3;
    var1=var2=var3=4;
    printf("%d", var1);
    printf("%d", var2);
    printf("%d", var3);
    return 0;
}
# Data Types and it's Sizes
#include<stdio.h>
int main()
{
  printf("%d",sizeof(int))
  printf("%d",sizeof(short int))
  printf("%d",sizeof(long int))
  printf("%d",sizeof(signed int))
  printf("%d",sizeof(unsigned int))
  printf("%d",sizeof(float))
  printf("%d",sizeof(char))
  printf("%d",sizeof(double))
  printf("%d",sizeof(void))
  return 0;
}
# data type based 
//range of integers data type
#include<stdio.h>
#include<limits.h>
int main()
{
  int var1=INT_MIN;
  int var2=INT_MAX;
  printf("%d to %d", var1,var2);
  return 0;
}
//unsigned integers
#include<stdio.h>
#include<limits.h>
int main()
{
  unsigned int var1=INT_MIN;
  unsigned int var2=INT_MAX;
  printf("%u to %u", var1,var2);
  return 0;
}
or 
//unsigned integers
#include<stdio.h>
#include<limits.h>
int main()
{
  unsigned int var1=0;
  unsigned int var2=INT_MAX;
  printf("%d to %d", var1,var2);
  return 0;
}
or 
#include<stdio.h>
#include<limits.h>
int main()
{
  unsigned int var1=0;
  unsigned int var2=UINT_MAX;
  printf("%u to %u", var1,var2);
  return 0;
}
# short int 
#include<stdio.h>
#include<limits.h>
int main()
{
  short int var1=SHRT_MIN;
  short int var2=SHRT_MAX;
  printf("%d to %d", var1,var2);
  return 0;
}
