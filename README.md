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
//Initialization
int i,x,y,num,n;
char ch;
int ans = 0;

//What Operation is to be Performed
printf("Which operation do you want to perform?");
printf("Enter :\n		'a' for addition\n	's' for subtraction\n	'm' for multiplication\n	'd' for division\n\n");
scanf("%c", ch);

switch(ch){
	case 'a':
        //Adding two numbers
		printf("Enter two numbers consecutively");
		scanf( "%d%d", &x,&y);
		num = add( x, y);
		printf("the sum is %d\n\n", num);
        break;
    case 's' :
        //Subtracting two numbers
		printf("Enter two numbers consecutively");
		scanf( "%d%d", &x,&y);
		num =sub( x, y);
		printf("the difference is %d\n\n", num);
        break;
    case 'm' :
        //Multiplying two numbers
		printf("Enter two numbers consecutively");
		scanf( "%d%d", &x,&y);
		num = mul( x, y);
		printf("the product is %d\n\n", num);
        break;
    case 'd' :
        //Dividing two numbers
		printf("Enter two numbers consecutively");
		scanf( "%d%d", &x,&y);
		num = dev( x, y);
		printf("the quotient is %d\n\n", num);
        break;
        
}




//Adding two numbers
printf("Enter two numbers consecutively");
scanf( "%d%d", &x,&y);
num = add( x, y);
printf("the sum is %d\n\n", num);

//Subtracting two numbers
printf("Enter two numbers consecutively");
scanf( "%d%d", &x,&y);
num =sub( x, y);
printf("the difference is %d\n\n", num);

//Multiplying two numbers
printf("Enter two numbers consecutively");
scanf( "%d%d", &x,&y);
num = mul( x, y);
printf("the product is %d\n\n", num);

//Dividing two numbers
printf("Enter two numbers consecutively");
scanf( "%d%d", &x,&y);
num = dev( x, y);
printf("the quotient is %d\n\n", num);
return 0;
}
