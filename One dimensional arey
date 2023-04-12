#include<stdio.h>

int main() {
    int n, i, j, temp;
    float average;
    printf("Enter the number of elements in the array: ");
    scanf("%d", &n);
   int arr[n];
    printf("Enter the elements of the array:\n");
    for(i = 0; i < n; i++)
    {
    scanf("%d", &arr[i]);
    }
   for(i = 0; i < n; i++)
    {
        for(j = i+1; j < n; j++)
        {
            if(arr[i] < arr[j])
            {
                temp = arr[i];
                arr[i] = arr[j];
                arr[j] = temp;
     }
     }
     }
    int secondLargest = arr[1];
    int smallest = arr[n-1];
    for(i = 1; i < n; i++)
    {
        if(arr[i] < smallest) 
        {
            smallest = arr[i];
        }
        if(arr[i] > secondLargest && arr[i] != arr[0])
        {
            secondLargest = arr[i];
        }
    } average = (float)(secondLargest + smallest) / 2;
   for(i = 0; i < n; i++) 
    {
        if(arr[i] == average) 
        {
            printf("The second largest and smallest elements are %d and %d respectively.\n", secondLargest, smallest);
            printf("The average of %d and %d is %f, which is present in the given array.\n", secondLargest, smallest, average);
            return 0;
        }
    }
    printf("The second largest and smallest elements are %d and %d respectively.\n", secondLargest, smallest);
    printf("The average of %d and %d is %f, which is not present in the given array.\n", secondLargest, smallest, average);
    return 0;
}
