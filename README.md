#include<stdio.h>
int main()
{
int*p= malloc(2* sizeof(int));
p[0]=00;
p[1]=88;
printf("data :%d %d \n", p[0],p[1]);
free(p);
p=null;
printf("%d", p[0]);
printf("%d", p[1]);
return 0;
}
