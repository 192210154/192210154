#include<stdio.h> 
int maxDiff(int arr[], int n) 
{ 
 int diff[n-1]; 
 for (int i=0; i < n-1; i++) 
 diff[i] = arr[i+1] - arr[i]; 
 int max_diff = diff[0]; 
 for (int i=1; i<n-1; i++) 
 { 
 if (diff[i-1] > 0) 
 diff[i] += diff[i-1]; 
if (max_diff < diff[i]) 
 max_diff = diff[i]; 
 } 
 return max_diff; 
} 
int main() 
{ 
 int arr[] = {80, 2, 6, 3, 100}; 
 int size = sizeof(arr)/sizeof(arr[0]); 
 printf("Maximum difference is %d",  maxDiff(arr, size)); 
 return 0; 
}
