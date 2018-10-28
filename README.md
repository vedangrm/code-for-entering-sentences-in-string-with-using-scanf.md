# code-for-entering-sentences-in-string-with-using-scanf.md

\#include<stdio.h>

int main ()

{

char str[100];

printf("enter the string\n");

scanf("%[^\t]",str);

printf("the string is :\n");

printf("%s",str);

return 0;

}

