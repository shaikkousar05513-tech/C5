# C5
// program
#include<stdio.h>
int main(){
    int loop,n;
    loop=1;
    printf("enter the value of n:");
    scanf("%d",&n);
    do{
        printf("%d ");
        loop++;
    }    while(loop<=n);
    return 0;
}
