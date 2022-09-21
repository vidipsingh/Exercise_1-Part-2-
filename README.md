# Exercise_1-Part-2-

#include <stdio.h>

int main()
{
    int a;
    printf("Enter the number you want multiplication of : ");
    scanf("%d", &a);

for (int i = 1; i < 11; i++)
    {
        printf("%d X %d = %d\n", a, i, a * i);
    }
    return 0;
}
