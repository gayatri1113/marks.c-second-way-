//# marks.c-second-way//
#include<stdio.h>
int main()
{
    int m1,m2,m3,m4,m5,total;
    float per;
    printf("Enter s1 marks");
    scanf("%d",&m1);
    printf("Enter s2 marks");
    scanf("%d",&m2);
    printf("Enter s3 marks");
    scanf("%d",&m3);
    printf("Enter s4 marks");
    scanf("%d",&m4);
    printf("Enter s5 marks");
    scanf("%d",&m5);
    total=m1+m2+m3+m4+m5;
    per=total/5;
    printf("total marks=%d\n",total);
    printf("percentage=%f\n",per);
    return 0;
}
