# c-3
Nivens number

#include <stdio.h>
int main()
{
    int num,digit,sum=0;
    printf("enter the value:");
    scanf("%d",&num);
    while(num>0){
        digit=num%10;
        sum+=digit;
        num/=10;
    }
    if(num%sum==0){
        printf("%d is a nivens number.\n",num);
    }else{
        printf("%d is not a nivens number.\n",num);
    }
    return 0;
}
