<div align="center">

## Day of the week\(2002\)


</div>

### Description

Its a simple program which calculates the day of the week for any given date & month of the year 2002.
 
### More Info
 
Name & date of the month for the year 2002.

The logic is explained clearly in the program.With it even u can find out the day of the week for any year.

Its calculated using a "key number" for a month.This can be understood from the "comment statements" in the program.

So go & find out the "trick" & then you can impress all your friends by telling them the "day of the week" for any month & date of yhe year.

Do not forget to rate my progarm.

It returns the "day of the week" for the given month & date of the year 2002.

Nill.


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[manish soni](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/manish-soni.md)
**Level**          |Beginner
**User Rating**    |5.0 (15 globes from 3 users)
**Compatibility**  |C, C\+\+ \(general\), Borland C\+\+
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__3-1.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/manish-soni-day-of-the-week-2002__3-3322/archive/master.zip)

### API Declarations

```
#include<stdio.h>
#include<conio.h>
#include<iostream.h>
```


### Source Code

```
/*
Name: Manish soni.
E-Mail: manish_99us@yahoo.com
Language: C++
Category: Miscellaneous.
Description: Its a simple program which calculates the day of the week for any given date & month of the year 2002.
*/
#include<stdio.h>     //include files.
#include<conio.h>
#include<iostream.h>
void main()       //main function definition.
{
int opt,date,day;    //variable declaration.
char b;
cout<<"****A program to find out the day of the week for any date of the year 2002****\n\n";
cout<<"1.January\n2.February\n3.March\n4.April\n5.May\n6.June\n7.july\n8.August\n9.September\n10.October\n11.November\n12.December\n";
a: cout<<"\nEnter the value of the month:";
cin>>opt;
cout<<"\nEnter the date of the month:";
cin>>date;
/*Calculates the value of the variable 'day'.
 This will be the final result based on which the "day of the week" is calculated.
 day= ((month number + date of the month)%number of days in a week);
 month number is as follows:
    "6" if the 1st day of the month is "sunday".
    "7" if the 1st day of the month is "monday".
    "8" if the 1st day of the month is "tuesday".
    "9" if the 1st day of the month is "wednesday".
    "10" if the 1st day of the month is "thursday".
    "11" if the 1st day of the month is "friday".
    "12" if the 1st day of the month is "saturday".
*/
switch(opt)
{
case 1: if(date<=31)
{day=(8+date)%7;}
else
cout<<"\nFor u'r kind information january has only 31 days.\n";
break;
case 2: if(date<=28)
{day=(11+date)%7;}
else
cout<<"\nFor u'r kind information february has only 28 days.\n";
break;
case 3: if(date<=31)
{day=(11+date)%7;}
else
cout<<"\nFor u'r kind information march has only 31 days.\n";
break;
case 4: if(date<=30)
{day=(7+date)%7;}
else
cout<<"\nFor u'r kind information april has only 30 days.\n";
break;
case 5: if(date<=31)
{day=(9+date)%7;}
else
cout<<"\nFor u'r kind information may has only 31 days.\n";
break;
case 6: if(date<=30)
{day=(12+date)%7;}
else
cout<<"\nFor u'r kind information june has only 30 days.\n";
break;
case 7: if(date<=31)
{day=(7+date)%7;}
else
cout<<"\nFor u'r kind information july has only 31 days.\n";
break;
case 8: if(date<=31)
{day=(10+date)%7;}
else
cout<<"\nFor u'r kind information august has only 31 days.\n";
break;
case 9: if(date<=30)
{day=(6+date)%7;}
else
cout<<"\nFor u'r kind information september has only 30 days.\n";
break;
case 10: if(date<=31)
{day=(8+date)%7;}
else
cout<<"\nFor u'r kind information october has only 31 days.\n";
break;
case 11: if(date<=30)
{day=(11+date)%7;}
else
cout<<"\nFor u'r kind information november has only 30 days.\n";
break;
case 12: if(date<=31)
{day=(6+date)%7;}
else
cout<<"\nFor u'r kind information december has only 31 days.\n";
break;
}
/* The value of the variable 'day' calculated above is checked for the conditions:
  if (day==0) then the day of the week is "sunday".
  if (day==1) then the day of the week is "monday".
  if (day==2) then the day of the week is "tuesday".
  if (day==3) then the day of the week is "wednesday".
  if (day==4) then the day of the week is "thursday".
  if (day==5) then the day of the week is "friday".
  if (day==6) then the day of the week is "saturday".
*/
if(day==0)
{cout<<"\nIts SUNDAY.\n";}
if(day==1)
{cout<<"\nIts MONDAY.\n";}
if(day==2)
{cout<<"\nIts TUESDAY.\n";}
if(day==3)
{cout<<"\nIts WEDNESDAY.\n";}
if(day==4)
{cout<<"\nIts THURSDAY.\n";}
if(day==5)
{cout<<"\nIts FRIDAY.\n";}
if(day==6)
{cout<<"\nIts SATURDAY.\n";}
cout<<"\n****************************************************\n";
cout<<"\nWould u like to continue?[y/n]:";
cin>>b;
if(b=='y'||b== 'Y')
goto a;
else
getch();
getch();
}
```

