# circle
#include <stdio.h>
#define PI 3.14159
double area(double radius) {
    return PI * radius * radius;
    double calculateCircumference(double radius) {
    return 2 * PI * radius;
}
}



int main() {
    double radius, circleArea, circleCircumference;

    printf("Enter the radius of the circle: ");
    scanf("%lf", &radius);
    circleArea = area(radius);
    circleCircumference = circumference(radius);
     printf("Area of the circle: %.2lf\n", circleArea);
   double radius;
    printf("Enter the radius of the circle: ");
    scanf("%lf", &radius);
    double circumference = calculateCircumference(radius);





    return 0;
}
