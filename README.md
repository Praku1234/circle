# circle
#include <stdio.h>
#define PI 3.14159
double area(double radius) {
    return PI * radius * radius;
}



int main() {
    double radius, circleArea, circleCircumference,dia;

    printf("Enter the radius of the circle: ");
    scanf("%lf", &radius);
    circleArea = area(radius);
    dia = radius*2;
    circleCircumference = circumference(radius);
     printf("Area of the circle: %.2lf\n", circleArea);
     printf("diameter of the circle: ",dia);
     
  





    return 0;
}
