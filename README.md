# Force-of-two


#include <stdio.h>
#include <math.h>

int main(){


// Sayının 2'nin kuvveti olup olmadığını bulan program.

unsigned int EnterValue,i,temp;

printf("kontrol etmek istediginiz degeri giriniz:\n");
scanf("%u",&EnterValue);

int c;
c = !(EnterValue&(EnterValue-1));

if (c == 1)
{
    printf("kuvvetidir");
}
else
{
    printf("kuvveti degildir.");
}

    return 0;
}

