#include <stdio.h>

int main() {
    // Write C code here
    int u;
    int a;
    int s;

    int v2;
    
    printf("Third equation of motion: \n Enter the initial velocity= ");
    scanf("%d",&u);
    printf("Enter the accleration: ");
    scanf("%d",&a);
    printf("Enter the total displacement: ");
    scanf("%d",&s);

    v2=u*u+2*a*s;

    printf("v^2= %d",v2);
        

    return 0;
}
