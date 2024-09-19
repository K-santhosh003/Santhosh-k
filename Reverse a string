// C Program to Reverse a String using Two-Pointer Technique
#include <stdio.h>
#include <string.h>

void reverse(char* str) {

    // Initialize first and last pointers
    int first = 0;
    int last = strlen(str) - 1;
    char temp;

    // Swap characters till first and last meet
    while (first < last) {
      
        // Swap characters
        temp = str[first];
        str[first] = str[last];
        str[last] = temp;

        // Move pointers towards each other
        first++;
        last--;
    }
}

int main() {
    char str[100] = "Hello World";
    
      // Reversing str
    reverse(str);
  
    printf("%s\n", str);
    return 0;
}
