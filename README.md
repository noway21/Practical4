#include <stdio.h>

int main() {
    unsigned int n = 21; 

    int count = 0;

    for (unsigned int i = 1; i <= n; i++) {
        if (n % i == i) { 
            count++;
        }
    }

    printf("Кількість рівних дільників для числа %u (де n = 21): %d\n", n, count);

    return 0;
}
