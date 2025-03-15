# c-6
double pointers
#include <stdio.h>
void update(int*p){
    *p=50;
}
int main()
{
    int a=100;
    int*ptr=&a;
    int**pptr=&ptr;
    printf("given value:%d\n",a);
    printf("single ptr value:%d\n",*ptr);
    printf("double ptr value:%d\n",**pptr);
    return 0;
}
