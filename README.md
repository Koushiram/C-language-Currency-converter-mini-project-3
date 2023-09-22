#include <stdio.h>

 int
main ()
{
  
float amount, convertedAmount;
  
int choice;
  
 
printf ("Currency Converter\n");
  
printf ("1. USD to EUR\n");
  
printf ("2. EUR to USD\n");
  
printf ("3. USD to GBP\n");
  
printf ("4. GBP to USD\n");
  
printf ("5. EUR to GBP\n");
  
printf ("6. GBP to EUR\n");
  
printf ("Enter your choice: ");
  
scanf ("%d", &choice);
  
 
printf ("Enter the amount: ");
  
scanf ("%f", &amount);
  
 
switch (choice)
    {
    
case 1:
      
convertedAmount = amount * 0.85;
      
printf ("Converted amount: %.2f EUR\n", convertedAmount);
      
break;
    
case 2:
      
convertedAmount = amount * 1.18;
      
printf ("Converted amount: %.2f USD\n", convertedAmount);
      
break;
    
case 3:
      
convertedAmount = amount * 0.72;
      
printf ("Converted amount: %.2f GBP\n", convertedAmount);
      
break;
    
case 4:
      
convertedAmount = amount * 1.39;
      
printf ("Converted amount: %.2f USD\n", convertedAmount);
      
break;
    
case 5:
      
convertedAmount = amount * 0.86;
      
printf ("Converted amount: %.2f GBP\n", convertedAmount);
      
break;
    
case 6:
      
convertedAmount = amount * 1.16;
      
printf ("Converted amount: %.2f EUR\n", convertedAmount);
      
break;
    
default:
      
printf ("Invalid choice\n");
      
break;
    
}
  
 
return 0;

}


