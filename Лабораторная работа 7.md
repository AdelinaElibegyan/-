#define _CRT_SECURE_NO_WARNINGS
#include <stdio.h>
#include <locale.h>
#include <stdlib.h>
#include <math.h>
#define _CRT_NO_WARNINGS

void main()
{
  setlocale(LC_ALL, "RUS");//Задание 1
  char c;
  printf("Введите цифру или букву: ");
  scanf("%c", &c);
  switch (c){
  case '0':
    puts("Введена цифра.\n");
    break;
  case '1':
    puts("Введена цифра.\n");
    break;
  case '2':
    puts("Введена цифра.\n");
    break;
  case '3':
    puts("Введена цифра.\n");
    break;
  case '4':
    puts("Введена цифра.\n");
    break;
  case '5':
    puts("Введена цифра.\n");
    break;
  case '6':
    puts("Введена цифра.\n");
    break;
  case '7':
    puts("Введена цифра.\n");
    break;
  case '8':
    puts("Введена цифра.\n");
    break;
  case '9':
    puts("Введена цифра.\n");
    break;
  default:
    printf("Введена буква\n");
  }

  
  float x, y;//Задание 2
  char c;
  printf("Введите пример:\n");
  scanf("%f%c%f\n", &x, &c, &y);
  switch (c){
  case '+':
    printf("=%f\n", x + y);
    break;
  case '-':
    printf("=%f\n", x - y);
    break;
  case '*':
    printf("=%f\n", x * y);
    break;
  case '/':
    printf("=%f\n", x / y);
    break;
  default:
    printf("Пример не распознан\n");
    break;
  }
}
