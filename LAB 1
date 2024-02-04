#include <stdio.h>
#define N 5
int  stack[N];
int Top=-1;
int i;
void push(){
int x;
if(Top==N-1){
    printf("stack overflow!\n");
}
 else{
printf("Enter the element to be inserted");
scanf("%d",&x);
Top++;
stack[Top]=x;
}}
void pop()
{
    int item;
   if(Top==-1) {printf("stack underflow");
}   else{
    printf("element deleted is %d",stack[Top]);
    Top--;}
}
void display(){
printf("The elements in the stack are:");
for(i=Top;i>=0;i--)
    printf("%d",stack[i]);

}
void main(){
int choice;
printf("Enter 1 for push,2 for pop,3 for display\n");
scanf("%d",&choice);
do{
        switch(choice){
            case 1: push();
            break;
            case 2: pop();
            break;
            case 3:display();
            break;
            case 4:return;
            default: printf("you have entered the wrong number");
            break;}
            printf("enter 1.push,2.pop,3.display,4.stop\n");
            scanf("%d",&choice);
}while(choice!=4);
}
