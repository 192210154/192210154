#include <stdio.h>
#include <math.h>

// Define the union shape with two members
union Shape {
    float radius;
    struct {
        float length;
        float width;
    } rectangle;
};

int main() {
    union Shape shape;

    // Prompt the user to choose a shape
    char shapeType;
    printf("Enter shape type: (c for circle, r for rectangle)\n");
    scanf("%c", &shapeType);

    // Prompt the user to enter the shape's dimensions
    if (shapeType == 'c') {
        printf("Enter the radius of the circle:\n");
        scanf("%f", &shape.radius);

        // Calculate and print the area of the circle
        float area = M_PI * pow(shape.radius, 2);
        printf("Area of circle: %f\n", area);
    } else if (shapeType == 'r') {
        printf("Enter the length of the rectangle:\n");
        scanf("%f", &shape.rectangle.length);

        printf("Enter the width of the rectangle:\n");
        scanf("%f", &shape.rectangle.width);

        // Calculate and print the area of the rectangle
        float area = shape.rectangle.length * shape.rectangle.width;
        printf("Area of rectangle: %f\n", area);
    } else {
        printf("Invalid shape type!\n");
    }

    return 0;
}
