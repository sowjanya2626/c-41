# c-41
Printing the address values by using poiners
#include<stdio.h>
int main (){
  int a=10;
  int *ptr=&a;
printf ("value %d\n",a);
printf ("address%p\n",&a);
printf("pointer%p\n",ptr);
printf("address at stored points %d\n",*ptr);
return 0;

}
