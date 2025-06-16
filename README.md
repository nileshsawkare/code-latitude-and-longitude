*# code-latitude-and-longitude *#
#include <stdio.h>

int main() {
   char name_letter;
   int pincode;
   float height;
   double latitude, longitude;
   
  // printf("Enter first letter of your name: ");
   scanf("%c",&name_letter);
   //printf("Enter your pincode: ");
   scanf("%d",&pincode);
   //printf("Enter your height in feet: ");
   scanf("%f",&height);
   //printf("Enter your latitude and longitude of your address: ");
   scanf("%lf %lf", &latitude, &longitude);
   
   printf("here is what you have entered:\n");
   printf("first letter of your name %c:\n", name_letter);
   printf("pincode:%d\n", pincode);
   printf("height:%f\n", height);
   printf("location%lf %lf\n", latitude, longitude);
   return 0;
   
    return 0;
}
