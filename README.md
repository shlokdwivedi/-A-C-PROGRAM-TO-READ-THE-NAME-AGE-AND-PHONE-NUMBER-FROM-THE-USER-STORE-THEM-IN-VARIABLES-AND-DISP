# -A-C-PROGRAM-TO-READ-THE-NAME-AGE-AND-PHONE-NUMBER-FROM-THE-USER-STORE-THEM-IN-VARIABLES-AND-DISP
#include
 int main()
{
	printf("enter your name :");
	char name[15];
	scanf("%s" ,&name);
	printf("enter your age : ");
	int age = 0 ;
	scanf("%d" , &age );
	printf("enter your phone_number :");
	int phone_number [10] ;
	scanf ("%d" , &phone_number);
printf("you entered your name = %s , age = %d " ,name , age ); 
printf("your phone no = %d", phone_number);
