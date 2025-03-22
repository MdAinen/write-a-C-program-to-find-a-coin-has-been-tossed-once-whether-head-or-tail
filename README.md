#include <stdio.h> 
 
int main() { 
    srand(time(NULL));  
    int toss = rand() % 2; // Generates either 0 or 1 
    if (toss == 0) { 
        printf("Heads\n"); 
    } else { 
        printf("Tails\n"); 
    } 
    return 0; 
} 
