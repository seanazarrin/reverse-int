#include <stdio.h>

int main(){
    
    int x,y,temp1;
    int z=0;
    scanf("%d",&x);
    while(x>=1){
         temp1=x%10;
         x=x/10;
         z=z*10+temp1;
    }
    printf("%d",z);
    return 0;
}
