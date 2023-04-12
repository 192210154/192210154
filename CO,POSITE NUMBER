#include <stdio.h>


int isComposite(int n) {
    int i;
    for(i=2; i<=n/2; i++) {
        if(n%i == 0) {
            return 1; 
        }
    }
    return 0; 
}

int main() {
    int n;
    printf("Enter a number: ");
    scanf("%d", &n);
    
    if(isComposite(n)) {
        printf("%d is a composite number.", n);
    }
    else {
        printf("%d is not a composite number.", n);
    }
    
    return 0;
}
