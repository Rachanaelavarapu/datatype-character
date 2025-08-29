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
# return to initial val
#include<stdio.h>
int main()
{
  unsigned int var=234;
  printf("%u", var);
  return 0;
}
//if the value is increased based on previous value the output will become 0
#include<stdio.h>
int main()
{
  unsigned int var=237;
  printf("%u", var);
  return 0;
}

# datattype-character
//character is represented as a 8bits of information
// character datatype is stored one character at a time
#include<stdio.h>
int main()
{
  char var='A';
  printf("%u", var);
  return 0;
}     //o/p= 65
or 
#include<stdio.h>
int main()
{
  unsigned int var=65;
  printf("%c", var);
  return 0;
}    //op=A
# range of character
// unsigned=0 to 266 and signed=-128 to 127
#include<stdio.h>
int main()
{
  char var=234;
  printf("%c", var);
  return 0;
}
