
#include <stdio.h>
#include <string.h>

void main()
{
    int rl,python,cprogramming,maths,physics,total;
    float per;
    char nm[20],div[10];
    printf("Input the Roll Number of the student :");
    scanf("%d",&rl);
    printf("Input the Name of the Student :");
    scanf("%s",nm);
    printf("Input  the marks of python,c programming,maths,physics : ");
    scanf("%d""%d""%d""%d",&python,&cprogramming,&maths,&physics);
    total =python+cprogramming+maths+physics;
    per = total/4.0;
    if (per>=60)
	 strcpy(div,"First");
    else
	if (per<60&&per>=48)
	    strcpy(div,"Second");
	else
	    if (per<48&&per>=36)
		strcpy(div,"Pass");
	     else
		strcpy(div,"Fail");

       printf("\nRoll No : %d\nName of Student : %s\n",rl,nm);
       printf("Marks in python : %d\n Marks in cprogramming : %d\n Marks in maths  : %d\n marks in physics : %d\n",python,cprogramming,maths,physics);
       printf("Total Marks = %d\nPercentage = %5.2f\nDivision = %s\n",total,per,div);
}
