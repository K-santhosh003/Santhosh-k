// C Program to check for prime number using Simple Trial
// Division
#include <stdbool.h>
#include <stdio.h>

bool isPrime(int N) {
  
    // If number is less than/equal to 1, it is not prime
    if (N <= 1) {
        return false;
    }

    // Check for divisors from 2 to N-1
    for (int i = 2; i < N; i++) {
      
        // If N is divisible by any number in this range, it
        // is not prime
        if (N % i == 0) {
            return false;
        }
    }

    // If no divisors are found, it is prime
    return true;
}

int main() {
    int N = 29;
    printf("Is %d prime?\n", N);

    if (isPrime(N)) {
        printf("Yes");
    }
    else {
        printf("No");
    }

    return 0;
}
