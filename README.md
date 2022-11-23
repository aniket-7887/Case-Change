# Case-Change
//This is a C program changes case of alphabet i.e., upper case to lower and vice versa
#include <stdio.h>

int main()
{
    char character;
    int temp;
    printf("Enter a character to change its case: ");
    scanf("%c", &character);
    if (character >= 65 && character <= 90)
    {
        temp=character+32;
    }
    else 
    {
        if (character >= 97 && character <= 122)
        {
            temp=character-32;
        }
        else
        {
            printf("It is not a character! Enter valid character.");
        }
        printf("Reversed character is %c", temp);
    }
    return 0;
}
