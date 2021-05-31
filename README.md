# pandalover27
# bank-management-system
#include<stdio.h>
#include<stdlib.h>
#include<conio.h>
#include<window.h>
Int i,j;
Int main_exit;
Int main() 
{
  Chat pass[10], password[10]="mycap";
  Int I=0;
  Printf("\n\n\t enter password to login") ;
  Scanf("%s", pass) ;
  If(pass[i]! =13&&pass[i]! =8) 
   {
      Printf(" ") ;
      Pass[i]=getch() ;
      I++;
    }
While(pass[i]! =13) ;
Pass[10]="\0";
If(strcmp(pass, password) ==0) 
{ 
  Printf("\n\n password match") ;
  For(I=0;I<=6;I++) 
   {
      Fordelay(1000) ;
      Printf(".") ;
   }
    System(" Cls") ;
    Menu() ;
  }
Else
{ 
   Printf("\n\n wrong password ") ;
   Printf(" Enter 1 to retry& 0 to exit") ;
   Scanf("%d", &main_exit) ;
   If(main_exit==1) 
     {
         System("cls") ;
         Main() ;
     }
Else if(main_exit==0) 
{
 System ("cls") ;
  Close () ;
}
Else
{
  Printf("\n invalid") ;
  Fordelay(1000) ;
  System("cls") ;
  Goto login_try;
}
} 
Return 0;
}
0 comments on commit aa4313c
@janhvikhatri
