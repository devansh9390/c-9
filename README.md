# c-9
linear data type
#include<stdio.h>
int main(){
    char names[3][20];
    int i;
    printf("enter 3 names:\n");
    for(i=0;i<3;i++){
        printf("name%d:",i+1);
        scanf("%s",names[i]);
    }
    printf("stored data:\n\n");
    for(i=0;i<3;i++){
        printf("name %d: %s\n",i+1,names[1]);
    }
    return 0;
}
