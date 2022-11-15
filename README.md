# FIND-LENGTH-OF-STRING-WITHOUT-USING-LIBRARY-FUNCTION



#include<stdio.h>
#include<string.h>

int main(){
    char str[10];
    int i, l=0;
    printf("FIND THE LENGTH OF STRING\n");
    printf("INPUT  A STRING\n");
    scanf("%s", &str);
    for(int i=0; i<str[i]!='\0'; i++)
    {
        l++;
    }
    printf("%s", l);
    printf("%s", str[1]);
}
