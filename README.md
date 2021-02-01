#include <stdio.h>

int main(void)
{
    int a = 7, b = 15;
    int res;
    
    res = a / b * 2;
    printf("res = %d\n", res);
    res = ++a * 9;
    printf("res = %d\n", res);
    res = a > b && a ! = 3;
    printf("res = %d\n", res);
    res = a % 5 == 0;
    printf("res = %d\n", res);
    
    return 0;
}
