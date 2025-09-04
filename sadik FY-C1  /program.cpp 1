#include <stdio.h>

int main() {
    int a = 10;
    int b = 20;

    int *const ptr = &a;

    printf("Before:\n");
    printf("Address ptr points to: %p\n", (void*)ptr);
    printf("Value at ptr: %d\n", *ptr);

    *ptr = 15;

    printf("\nAfter changing *ptr:\n");
    printf("Address ptr points to: %p\n", (void*)ptr);
    printf("Value at ptr: %d\n", *ptr);

    return 0;
}
