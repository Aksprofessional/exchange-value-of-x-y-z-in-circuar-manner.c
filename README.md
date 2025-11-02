# exchange-value-of-x-y-z-in-circuar-manner.c

// c program to exchange value of x,y,z in circuar manner.
#include <stdio.h>

int fun(int,int,int);

int main() {
    fun(5,8,10);//example
    return 0;
}

int fun(int x,int y,int z){
    int t,t2;
    while(y<10)//making it to work twice only
    {
        t=y;
        y=x;
        t2=z;
        z=t;
        x=t2;
        printf("%d\t%d\t%d\n",x,y,z);
    }
}
