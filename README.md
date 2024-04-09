#include <stdio.h>

int main() {
   
    int n,m;

    for(n = 1; n <= 1000; n++){
        printf("%d ", n);
        for (m = 1; m <= n*10000; m++);
    }
    return 0;
}

//두 번째 for문의 기능
