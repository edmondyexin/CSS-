```
#include "stdio.h"
// reduce 1 to n
int computeSum(int n){
    if(n>0){
        return computeSum(n-1)+n;
    }else{
        return 0;
    }
}
int main(){
    // input
    int n ;
    scanf("%d",&n);
    int sum = computeSum(n);
    printf("sum:%d",sum);
    return 0;
}

```

