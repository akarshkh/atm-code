/*write a c program to show working of an atm by taking amount as input from user and print no. 
of notes of 2000,500,200 and 100.
for eg. user input: 3300
then it gives like eg 1: 2000: 1
                         500;  2
                         200;  1
                         100;  1

                  eg 2: input=12600
                         2000:  6
                         500 :  1
                         200 :  0
                         100 :  1
                    */

#include<stdio.h>
int main()
{
int amt,tt,fh,th,h;
printf("enter the amount you want to withdraw ");
scanf("%d",&amt);
tt=(amt/2000);
printf("2000=%d\n",tt);
fh=(amt%2000);
printf("500=%d\n",fh/500);
th=fh%500;
printf("200=%d\n",th/200);
h=th%200;
printf("100=%d\n",h/100);
return 0;





}
