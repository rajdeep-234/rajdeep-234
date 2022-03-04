#include<stdio.h>

int main(){
    char country[5]="India";
    
    char currency='$';//Currency is in US Dollar
    
    float GDP=2.2;//here GDP GREW US$2.2 TRILLION
    
    int year=2015;//The year was 2015
    
    printf("The GDP Of %s grew five fold to reach US%c%.1f trillion in %d\n",country,currency,GDP,year);
    
    return 0;
}
