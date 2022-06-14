# prostoechislo

Для заданного числа 
N
N проверить, является ли оно простым.

Входные данные:
Одно натуральное число 
N
N, отличное от 1.

Выходные данные: 
1 -- если число простое
0 -- если число составное


#include <stdio.h>

int main() {
    int a, k = 0;
    scanf("%d", &a);
    for (int i = 1; i <= a; i++)
    {
        if (a % i == 0)
        {
            k++;
        }
    }
    if (k > 2)
        printf("0");
    else
        printf("1");
    return 0;
}
