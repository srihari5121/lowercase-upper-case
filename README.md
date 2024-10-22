# lowercase-upper-case

#include <stdio.h>

int main()
{
    char ch;
    printf("Enter the character:");
    scanf("%c",&ch);
    if(ch>=65 && ch<=90)
    {
        printf("lowercase:");
        printf("%c",ch+32);
    }
    else if (ch>=97 && ch<=122)
    {
        printf("lowercase:");
        printf("%c",ch-32);
    }
else
printf("Enter a proper character");
    return 0;
}
