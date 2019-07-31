# CalculatorKadasha
Calculator 
#include <stdio.h>
#include <stdlib.h>

int main(){
int num1, num2;

printf("Calculadora Kadasha\n\n");
printf("Por favor, Digite um Numero: \n");
scanf("%i", &num1);
printf("Por favor, Digite outro Numero: \n");
scanf("%i", &num2);

int soma = num1 + num2;
int sub = num1 - num2;
int multi = num1 * num2;
double div = num1 / num2;

printf("\n\nResultados:\n");

printf("\n%i + %i = %i\n", num1, num2, soma);
printf("\n%i - %i = %i\n", num1, num2, sub);
printf("\n%i * %i = %i\n", num1, num2, multi);
printf("\n%i / %i = %f\n", num1, num2, div);

return 0;
}
