I created this Celsius-to-Fahrenheit converter during my Algorithms and Programming Logic classes.
#include <stdio.h>
int main(){
    float celsius, fahrenheit;
    printf("Digite a temperatura em graus Celsius:");
    scanf("%f", &celsius);
    fahrenheit = ((celsius*9)/5) + 32;
    printf("\n%.2fº Celsius equivalem à: %.2fº Fahrenheit.", celsius,fahrenheit);
    return 0;
}
