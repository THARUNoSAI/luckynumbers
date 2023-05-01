#include <stdio.h>

int main() {
    int sum = 0, num, digit;
    printf("Summing up all even four-digit numbers...\n");
    for (num = 1000; num <= 9998; num += 2) {
        sum += num;
    }
    printf("Sum: %d\n", sum);
    while (sum > 9) {
        int tempSum = 0;
        while (sum > 0) {
            digit = sum % 10;
            tempSum += digit;
            sum /= 10;
        }
        sum = tempSum;
    }
    printf("Single digit: %d\n", sum);
    if (sum % 2 == 0) {
        printf("Even found\n");
    } else {
        printf("Odd found\n");
    }
    return 0;
}
