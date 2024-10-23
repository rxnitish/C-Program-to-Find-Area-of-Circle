#include <math.h> 
#include <stdio.h> 
#define PI 3.142 
  
// Function to find the area of 
// of the circle 
double findArea(int r) { return PI * r * r; } 
  
// Driver code 
int main() 
{ 
    printf("Area is %f", findArea(5)); 
    return 0; 
}
