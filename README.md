code-code
=========

#include <stdio.h>


int add(int i,int j)
{
int k;
k = i+j;
return k;
}

int sub(int i,int j)
{
int k;
k = i-j;
return k;
}

int mul(int i,int j)
{
int k;
k = i*j;
return k;
}
int dev(int i,int j)
{
int k;
k = i/j;
return k;
}

int main(){
int i,x,y,num,n;
int ans = 0;
printf("Enter an integer number");
scanf("%d",&n);
printf("the array of all integers upto %d is the datta_array", n);
for(i=0;i<n;i++){
	printf("the datta_array element number %d is %d\n", i,i);
}

#Inputting arguments for adding
printf("Enter two numbers consecutively");
scanf( "%d%d", &x,&y);
num = add( x, y);
printf("the patelsum is %d\n\n", num);


return 0;
}
