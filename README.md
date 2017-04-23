# c-program
simple 'call by value' code for begineers.


#include<stdio.h>
int sum(int a) //formal argument
{
  int s;
  return (s=a+1);
}
int main()
{
  int a=10;
  int s=sum(s); //actual argument
  printf("Sum of number is s=%d",s);
}  
