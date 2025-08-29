# my-school-project//Rockview university-main campus
//ict 113
//student name: Peter mufaya
//student No: 2025550296

#include <stdio.h>

int main()
{
//variables to store the age
int age;
//message to user
printf("please enter your age:" );

//prompt the user for age and assign it to variables
scanf("%d, &age");
//check age and show message 
if (age < 0)
{ // if user enters negative value
printf("please enter positive number!\n");
}
else if (age < 13)
{// child condition
printf("you are a child! \n");
}
else if( age >=12 <=19)
{//teenager condition 
printf("you are a teenager: \n");
}
else
{ //adult default 
printf("you are an adult: \n");
}

return 0;
//end 
}
