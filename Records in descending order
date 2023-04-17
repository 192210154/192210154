#include<stdio.h>
#include<conio.h>
void main()
 {
 struct student
 {
 int rollno;
 char name[20];
 int marks[3];
 int total;
 float avg;
 }stud[2];
 int i,j;
 struct student temp;
 clrscr();
 printf("\n enter studentinfo");
 for(i=0;i<2;i++)
  {
  printf("\n enter rollno");
  scanf("\n %d",&stud[i].rollno);
  printf("\n enter name");
  scanf("\n %s",&stud[i].name);
  stud[i].total=0;
  printf("\n enter marks");

  for(j=0;j<3;j++)
   {
   scanf("\n %d",&stud[i].marks[j]);

   stud[i].total=stud[i].total+stud[i].marks[j] ;
   stud[i].avg=stud[i].total/3;
   }
  }
  for(i=0;i<2;i++)
   {
   for(j=i+1;j<2;j++)
            {
            if(stud[i].total<stud[j].total)
             {
             temp=stud[i];
             stud[i]=stud[j];
             stud[j]=temp;
             }
            }
   }
   printf("\n the student info are");
            printf("\n ROLLNO    NAME TOTAL  AVG");
   for(i=0;i<2;i++)
            {
             printf("\n %d\t %s\t %d\t %f",stud[i].rollno,stud[i].name,stud[i].total,stud[i].avg);

            }
  getch();
 }
