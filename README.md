#include <stdio.h>
int main()
{
printf("\n enter the value ofa and b\n");
scanf("%d %d" &a,&b);
printf("\n before swap:a=%d b=%d\n",a,b);
a=a^b;
b=a^b;
a=a^b;
return 0;
