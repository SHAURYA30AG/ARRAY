
#include <stdio.h>

int main()
{
    int arr[10];

    printf("Enter Elements in array :-- \n");

    for (int i = 0; i < 10; i++)
    {
        scanf("%d", &arr[i]);
    }

    printf("Elements of array :-- ");

    for (int i = 0; i < 10; i++)
    {
        printf("%d ", arr[i]);
    }
}
