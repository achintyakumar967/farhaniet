# farhaniet
#include <stdio.h>
int centigrade();
int Fahrenheit();
int main(){
    Fahrenheit();
    centigrade();
}
int Fahrenheit(){
    float f,c;
    printf("enter value of Fahrenheit :");
    scanf("%f",&f);
    c=(f-32.0)*(5.0/9.0);
    printf("centigrade=%.2f\n",c);
     return 0;
}
int centigrade(){
    float f,c;
    printf("enter value of centigrade  :");
    scanf("%f",&f);
    f=(c*(9.0/5.0)+32.0);
    printf("Fahrenheit=%.2f",f);
     return 0;
}
