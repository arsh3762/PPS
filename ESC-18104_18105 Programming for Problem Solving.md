
![](https://i.imgur.com/wg8UysY.jpg)

----
# ESC-18104/18105 Programming for Problem Solving
----
**Name-** Arshdeep Swarn 
**Branch-** CSE 
**SECTION**- C2
**ROLL NUMBER-** 1915303

----
## 1. TO PRINT NAME USING PUTS
    include<stdio.h> 
    int main() 
    { 
    puts("My Name is Arshdeep Swarn");
    return 0; 
    }
*OUTPUT;*
![](https://i.imgur.com/3uV0Af8.png?3)

----
## 2. TO PRINT COLLEGE ADDRESS
     #include<stdio.h> 
    int main() 
     { 
    puts("Guru Nanak Dev Engineering College,");
    puts("Gill Road,");
    puts("Ludhiana,Punjab,");
    return 0; 
    }
*OUTPUT;*
![](https://i.imgur.com/9kUIBty.png?1)

----
## 3. PROGRAM TO ADD THREE INTEGERS

    #include<stdio.h>
	int main()
	{
	   int a, b, c;
	   
	   printf("Enter two numbers to add\n");
	   scanf("%d%d", &a, &b);
	   
	   c = a + b;
	   
	   printf("Sum of the numbers = %d\n", c);
	   
	   return 0;
	}
*OUTPUT;*
![](https://i.imgur.com/2tQo4rc.png)

----
## 4. PROGRAM TO FIND QUOTIENT AND REMAINDER


    #include <stdio.h>
 
 
 
    int main()
      {
           int dividend, divisor, quotient, remainder;
    printf("Enter dividend: ");
    scanf("%d", &dividend);
    printf("Enter divisor: ");
    scanf("%d", &divisor);
    
     quotient = dividend / divisor;
   
     remainder = dividend % divisor;
     printf("Quotient = %d\n", quotient);
      printf("Remainder = %d\n", remainder);
     return 0;
     }
*OUTPUT;*
![](https://i.imgur.com/yqEQjcX.png)

----
## 5. Program to swap two variables without 3rd variable.
    #include<stdio.h>  
     int main()    
     {       
    int a=10, b=20;      
     printf("Before swap a=%d b=%d\n",a,b);      
     a=a+b;//a=30 (10+20)    
      b=a-b;//b=10 (30-20)    
      a=a-b;//a=20 (30-10)    
     printf("After swap a=%d b=%d\n
    ",a,b); 
    return 0;  
    }   
*OUTPUT;*
![](https://i.imgur.com/gRaCYiL.png)

----
## 6. PROGRAM TO CHECK EVEN OR ODD

    #include <stdio.h>
     int main()
    {
    int number;
    printf("Enter an integer: ");
    scanf("%d", &number);
    if(number % 2 == 0)
        printf("%d is even.", number);
    else
        printf("%d is odd.", number);
    return 0;
     }
*OUTPUT;*
![](https://i.imgur.com/y7rR1tE.png)

----
## 7.FIND GREATEST OF TWO NUMBER

    #include <stdio.h>  
   
    int main() {  
    int a, b;  
    printf("Please Enter Two different values\n");  
    scanf("%d %d", &a, &b);  
    
    if(a > b) 
    {
        printf("%d is Largest\n", a);          
    } 
    else if (b > a)
    }
        printf("%d is Largest\n", b);  
    } 
    else 
    {
	printf("Both are Equal\n");
    }
   
    return 0;  
     }

*OUTPUT;*
![](https://i.imgur.com/GquEFx5.png)

----
## 8. FIND GREATEST OF THREE NUMBER
    #include <stdio.h>
    int main()
    {
    double n1, n2, n3;
    printf("Enter three different numbers: ");
    scanf("%lf %lf %lf", &n1, &n2, &n3);
    if( n1>=n2 && n1>=n3 )
        printf("%.2f is the largest number.\n", n1);
    if( n2>=n1 && n2>=n3 )
        printf("%.2f is the largest number.\n", n2);
    if( n3>=n1 && n3>=n2 )
        printf("%.2f is the largest number.\n", n3);
    return 0;
    }

*OUTPUT;*
![](https://i.imgur.com/6wIvyBU.png)

----
## 9. PROGRAM TO ASSIGN GRADE TO STUDENTS
    #include<stdio.h>
    void main()
    {
    int marks;
    printf("Enter your marks ");
    scanf("%d",&marks);
    if(marks<0 || marks>100)
    {
        printf("Wrong Entry");
    }
    else if(marks<50)
    {
        printf("Grade F");
    }
    else if(marks>=50 && marks<60)
    {
        printf("Grade D");
    }
    else if(marks>=60 && marks<70)
    {
        printf("Grade C");
    }
    else if(marks>=70 && marks<80)
    {
        printf("Grade B");
    }
    else if(marks>=80 && marks<90)
    {
        printf("Grade A");
    }
    else
    {
        printf("Grade A+");
    }
     }
*OUTPUT;*
![](https://i.imgur.com/AFUZ9rx.png)

----
## 10. PROGRAM TO FIND ROOTS OF QUADRATIC EQUATION

    #include <stdio.h>
    #include <math.h>
    int main()
    {
    double a, b, c, discriminant, root1, root2, realPart, imaginaryPart;
    printf("Enter coefficients a, b and c: ");
    scanf("%lf %lf %lf",&a, &b, &c);
    discriminant = b*b-4*a*c;
    if (discriminant > 0)
    {
        root1 = (-b+sqrt(discriminant))/(2*a);
        root2 = (-b-sqrt(discriminant))/(2*a);
        printf("root1 = %.2lf and root2 = %.2lf",root1 , root2);
    }
    else if (discriminant == 0)
    {
        root1 = root2 = -b/(2*a);
        printf("root1 = root2 = %.2lf;", root1);
    }
    else
    {
        realPart = -b/(2*a);
        imaginaryPart = sqrt(-discriminant)/(2*a);
        printf("root1 = %.2lf+%.2lfi and root2 = %.2f-%.2fi", realPart, imaginaryPart, realPart, imaginaryPart);
    }
    return 0;
     }
*OUTPUT;*     
![](https://i.imgur.com/bilIPoF.png)

## 11. PROGRAM TO CHECK YEAR IS LEAP OR NOT

     #include <stdio.h>
     int main()
     {
    int year;
    printf("Enter a year: ");
    scanf("%d",&year);
    if(year%4 == 0)
    {
        if( year%100 == 0)
        {
            if ( year%400 == 0)
                printf("%d is a leap year.", year);
            else
                printf("%d is not a leap year.", year);
        }
        else
            printf("%d is a leap year.", year );
    }
    else
        printf("%d is not a leap year.", year);
    
    return 0;
    }
    
*OUTPUT; *   
![](https://i.imgur.com/pFpFSes.png)

----

## 12. PROGRAM TO PRINT TABLE OF 5

    #include <stdio.h>
    int main()
    {
    int n=5 , i;
    printf("Multiplcation table of 5\n");
    for(i=1; i<=10; ++i)
    {
        printf("%d * %d = %d \n", n, i, n*i);
    }
    
    return 0;
    }
    
*OUTPUT;*    
![](https://i.imgur.com/jWRs1Hg.png)

----
## 13. TO MAKE SIMPLE CALCULATOR USING SWITCH CASE

    #include <stdio.h>
    int main() {
    char operator;
    double firstNumber,secondNumber;
    printf("Enter an operator (+, -, *,): ");
    scanf("%c", &operator);
    printf("Enter two operands: ");
    scanf("%lf %lf",&firstNumber, &secondNumber);
    switch(operator)
    {
        case '+':
            printf("%.1lf + %.1lf = %.1lf",firstNumber, secondNumber, firstNumber + secondNumber);
            break;
        case '-':
            printf("%.1lf - %.1lf = %.1lf",firstNumber, secondNumber, firstNumber - secondNumber);
            break;
        case '*':
            printf("%.1lf * %.1lf = %.1lf",firstNumber, secondNumber, firstNumber * secondNumber);
            break;
        case '/':
            printf("%.1lf / %.1lf = %.1lf",firstNumber, secondNumber, firstNumber / secondNumber);
            break;
        default:
            printf("Error! operator is not correct");
    }
    
    return 0;
    }

*OUTPUT;*
![](https://i.imgur.com/c0HYsvs.png)

----
## 14. TO CALCULATE REVERSE OF A NUMBER
    #include <stdio.h>
 
    int main()
    {
     int n, reverse = 0;
 
     printf("Enter a number to reverse\n");
    scanf("%d", &n);
 
    while (n != 0)
    {
    reverse = reverse * 10;
    reverse = reverse + n%10;
    n = n/10;
    }
 
    printf("Reverse of entered number is = %d\n", reverse);
 
    return 0;
    }
    
*OUTPUT;*
![](https://i.imgur.com/ihmeiJD.png)    

----
## 15. TO CHECK WHETHER NUMBER IS PALLINDROME OR NOT

    #include <stdio.h>
 
    int main()
    {
     int n, r = 0, t;
 
    printf("Enter a number to check if it is a palindrome or not\n");
    scanf("%d", &n);
 
    t = n;
 
    while (t != 0)
    {
    r = r * 10;
    r = r + t%10;
    t = t/10;
     }
 
    if (n == r)
    printf("%d is a palindrome number.\n", n);
    else
    printf("%d isn't a palindrome number.\n", n);
 
    return 0 ;
     }
*OUTPUT;*     
![](https://i.imgur.com/CE15rUB.png)

----
## 16. TO CHECK NUMBER IS PRIME OR NOT
    #include <stdio.h>
    int main()
    {
     int i, num, p = 0;
     printf("Please enter a number: \n");
    scanf("%d", &num);
    for(i=1; i<=num; i++)
    {
      if(num%i==0)
      {
         p++;
      }
    }
     if(p==2)
    {
      printf("Entered number is %d "\
             "and it is a prime number.",num);
    }
    else
    {
      printf("Entered number is %d "\
             "and it is not a prime number.",num);
    } 
    }
*OUTPUT;*
![](https://i.imgur.com/IALNHnL.png)

----
## 17. PROGRAM TO PRINT PRIME NUMBER 1 TO 100 IN A LOOP
    #include <stdio.h>
 
    int main()
    {
    int i, Number, count; 
  
    printf(" Prime Number from 1 to 100 are: \n"); 
    for(Number = 1; Number <= 100; Number++)
    {
    count = 0;
    for (i = 2; i <= Number/2; i++)
    {
  	if(Number%i == 0)
  	{
     	  count++;
  	  break;
	}
    }
    if(count == 0 && Number != 1 )
    {
	printf(" %d ", Number);
    }  
    }
    return 0;
    } 
*OUTPUT;*    
![](https://i.imgur.com/4GhWj4V.png)

----
## 18. PROGRAM TO CHECK NUMBER IS ARMSTRONG OR NOT
    #include<stdio.h>  
    int main()    
    {    
    int n,r,sum=0,temp;    
    printf("enter the number=");    
    scanf("%d",&n);    
    temp=n;    
    while(n>0)    
    {    
    r=n%10;    
    sum=sum+(r*r*r);    
    n=n/10;    
    }
    if(temp==sum)
     printf("armstrong  number\n");    
    else    
    printf("not armstrong number\n");    
     return 0;  
    } 
    
*OUTPUT;*    
![](https://i.imgur.com/kGu7Tlz.png)

----
## 19. PRINT DIFFERENT PATTERNS

### PATTERN 1
    #include <stdio.h>
    int main()
    {
    int i, j, rows;
    printf("Enter number of rows: ");
    scanf("%d",&rows);
    for(i=1; i<=rows; ++i)
    {
        for(j=1; j<=i; ++j)
        {
            printf("%d ",j);
        }
        printf("\n");
    }
    return 0;
    }
    
*OUTPUT;*
![](https://i.imgur.com/wXb0zv9.png)

----
### PATTERN 2
    #include <stdio.h>
 
    int main()
    {
     int n, i,  c, a = 1;
 
     printf("Enter the number of rows:");
     scanf("%d", &n);
 
     for (i = 1; i <= n; i++)
    {
      for (c = 1; c <= i; c++)
    {
      printf("%d ",a);
      a++;
    }
    printf("\n");
    }
 
     return 0;
    }
*OUTPUT;*    
![](https://i.imgur.com/GKDiR2W.png)

----
### PATTERN 3
    #include <stdio.h>
    int main()
    {
      int i, space, rows, k=0, count = 0, count1 = 0;
    printf("Enter number of rows: ");
    scanf("%d",&rows);
    for(i=1; i<=rows; ++i)
    {
        for(space=1; space <= rows-i; ++space)
        {
            printf("  ");
            ++count;
        }
        while(k != 2*i-1)
        {
            if (count <= rows-1)
            {
                printf("%d ", i+k);
                ++count;
            }
            else
            {
                ++count1;
                printf("%d ", (i+k-2*count1));
            }
            ++k;
        }
        count1 = count = k = 0;
        printf("\n");
    }
    return 0;
    }
*OUTPUT;*
![](https://i.imgur.com/pzzqT9r.png?1)

----
## 20. PROGRAM TO FIND LARGEST FROM ONE DIMENSIONAL ARRAY
     #include <stdio.h>
 
    int main()
        {
 
        int array[50], size, i, largest;
 
        printf("Enter the size of the array: ");
	scanf("%d", &size);
 
        printf("Enter %d elements of  the array: ", size);
 
        for (i = 0; i < size; i++)
		scanf("%d", &array[i]);
 
        largest = array[0];
 
        for (i = 1; i < size; i++) 
        {
		if (largest < array[i])
			largest = array[i];
	}
 
        printf("Largest element present in the given array is : %d\n", largest);
 
        return 0;
 
    }
*OUTPUT;*    
 ![](https://i.imgur.com/PmzNfMc.png)   
 
----
## 21. TO FIND THE SUM OF N NATURAL NUMBERS
     #include <stdio.h>
 
    void main()
    {
    int i, num, sum = 0;
 
    printf("Enter an integer number \n");
    scanf ("%d", &num);
    for (i = 1; i <= num; i++)
    {
        sum = sum + i;
    }
    printf ("Sum of first %d natural numbers = %d\n", num, sum);
    }
*OUTPUT;* 
 ![](https://i.imgur.com/0zqWJgP.png)
 
----
## 22. PROGRAM TO ADD TWO MATRICES
     #include <stdio.h>
  
    int main()
    {
     int m, n, c, d, first[10][10], second[10][10], sum[10][10];
 
     printf("Enter the number of rows and columns of matrix\n");
     scanf("%d%d", &m, &n);
     printf("Enter the elements of first matrix\n");
 
     for (c = 0; c < m; c++)
        for (d = 0; d < n; d++)
         scanf("%d", &first[c][d]);
 
    printf("Enter the elements of second matrix\n");
 
    for (c = 0; c < m; c++)
      for (d = 0 ; d < n; d++)
         scanf("%d", &second[c][d]);
   
    printf("Sum of entered matrices:-\n");
   
    for (c = 0; c < m; c++) {
      for (d = 0 ; d < n; d++) {
         sum[c][d] = first[c][d] + second[c][d];
         printf("%d\t", sum[c][d]);
      }
      printf("\n");
    }
 
    return 0;
    }
*OUTPUT;*    
    ![](https://i.imgur.com/iVa6A0g.png)
    
----
## 23. PROGRAM TO MULTIPLY TWO MATRICES
    #include <stdio.h>
 
    int main()
    {
    int m, n, p, q, c, d, k, sum = 0;
    int first[10][10], second[10][10], multiply[10][10];
 
    printf("Enter number of rows and columns of first matrix\n");
    scanf("%d%d", &m, &n);
     printf("Enter elements of first matrix\n");
 
    for (c = 0; c < m; c++)
     for (d = 0; d < n; d++)
      scanf("%d", &first[c][d]);
 
    printf("Enter number of rows and columns of second matrix\n");
    scanf("%d%d", &p, &q);
 
     if (n != p)
    printf("The matrices can't be multiplied with each other.\n");
    else
    {
    printf("Enter elements of second matrix\n");
 
    for (c = 0; c < p; c++)
      for (d = 0; d < q; d++)
        scanf("%d", &second[c][d]);
 
    for (c = 0; c < m; c++) {
      for (d = 0; d < q; d++) {
        for (k = 0; k < p; k++) {
          sum = sum + first[c][k]*second[k][d];
        }
 
        multiply[c][d] = sum;
        sum = 0;
      }
    }
 
    printf("Product of the matrices:\n");
 
    for (c = 0; c < m; c++) {
      for (d = 0; d < q; d++)
        printf("%d\t", multiply[c][d]);
 
      printf("\n");
    }
     }
 
    return 0;
    }
    
*OUTPUT;*    
    ![](https://i.imgur.com/xbYidTq.png)
    
----
## 24. TO CHECK WHWTHER STRING IS PALLINDROME OR NOT
    #include <stdio.h>
    #include <string.h>

    int main(){
     char string1[20];
    int i, length;
    int flag = 0;
    
    printf("Enter a string:");
    scanf("%s", string1);
    
    length = strlen(string1);
    
    for(i=0;i < length ;i++){
        if(string1[i] != string1[length-i-1]){
            flag = 1;
            break;
      }
       }
    
    if (flag) {
        printf("%s is not a palindrome\n", string1);
    }    
    else {
        printf("%s is a palindrome\n", string1);
    }
    return 0;
    }
*OUTPUT;*
![](https://i.imgur.com/2rUgDXn.png)

----
## 25. Program to perform basic operations like lenghth of string ,string concat, string copy ,string compare and string reverse.
    #include <stdio.h> 
    #include <stdlib.h>
  
    int find_length(char string[]) {
    int len = 0, i;
    for (i = 0; string[i] != '\0'; i++) {
      len++;
    }
    return len;
     }

    void join_strings(char string1[], char string2[]) {
    int i, len1, len2;
     len1 = find_length(string1);
    len2 = find_length(string2);
     for (i = len1; i < len1 + len2; i++) {
    string1[i] = string2[i - len1];
     }
    string1[i] = '\0'; //adding null character at the end of input
    }
    /*returns 0 if thery are same otherwise returns 1*/

    int compare_strings(char string1[], char string2[]) {
     int len1, len2, i, count = 0;
     len1 = find_length(string1);
     len2 = find_length(string2);
      if (len1 != len2)
    return 1;
     for (i = 0; i < len1; i++) {
     if (string1[i] == string2[i])
      count++;
      }
     if (count == len1)
      return 0;
     return 1;
    }

    void copy_string(char destination[], char source[]) {
     int len, i;
     len = find_length(source);
     for (i = 0; i < len; i++) {
    destination[i] = source[i];
    }
     destination[i] = '\0';
    }

    int main() {
     char string1[20], string2[20]; //string variables declaration with size 20
     int choice;
    while (1) {
    printf("\n1. Find Length \n2. Concatenate \n3. Compare \n4. Copy \n5. Exit\n");
    printf("Enter your choice: ");
    scanf("%d", & choice);
    switch (choice) {
    case 1:
      printf("Enter the string: ");
      scanf("%s", string1);
      printf("The length of string is %d", find_length(string1));
      break;
    case 2:
      printf("Enter two strings: ");
      scanf("%s%s", string1, string2);
      join_strings(string1, string2);
      printf("The concatenated string is %s", string1);
      break;
    case 3:
      printf("Enter two strings: ");
      scanf("%s%s", string1, string2);
      if (compare_strings(string1, string2) == 0) {
        printf("They are equal");
      } else {
        printf("They are not equal");
      }
      break;
    case 4:
      printf("Enter a string: ");
      scanf("%s", string1);
      printf("String1 = %s\n");
      printf("After copying string1 to string 2\n");
      copy_string(string2, string1);
      printf("String2 = %s", string2);
      break;
    case 5:
      exit(0);
    }
     }
    return 0;
    }
*output;*
![](https://i.imgur.com/9MJoypW.png)

----
## 26. PROGRAM TO SWAP TWO NUMBERS BY CALL BY VALUE AND CALL BY REFERENCE

### A. SWAP BY VALUE

    #include <stdio.h>
 
 
     void swap(int, int);
 
    int main()
    {
     int x, y;
 
     printf("Enter the value of x and y\n");
     scanf("%d%d",&x,&y);
 
    printf("Before Swapping\nx = %d\ny = %d\n", x, y);
 
    swap(x, y); 
 
    printf("After Swapping\nx = %d\ny = %d\n", x, y);
 
    return 0;
    }
 
    void swap(int a, int b)
    {
    int temp;
 
     temp = b;
      b = a;
     a = temp;
    printf("Values of a and b is %d  %d\n",a,b);
     }

*OUTPUT;*
![](https://i.imgur.com/j4loQQL.png)

----
###  SWAP BY REFERENCE
    #include <stdio.h>

    void swap(int * num1, int * num2);

    int main()
     {
    int num1, num2;
    printf("Enter two numbers: ");
    scanf("%d%d", &num1, &num2);
    printf("Before swapping in main n");
    printf("Value of num1 = %d \n", num1);
    printf("Value of num2 = %d \n\n", num2);

    swap(&num1, &num2);
    printf("After swapping in main n");
    printf("Value of num1 = %d \n", num1);
    printf("Value of num2 = %d \n\n", num2);

    return 0;
    }

     void swap(int * num1, int * num2)
    {
     int temp;
    temp = *num1;

    *num1= *num2;

    *num2= temp;

    printf("After swapping in swap function n");
    printf("Value of num1 = %d \n", *num1);
    printf("Value of num2 = %d \n\n", *num2);
    }
*OUTPUT;*
![](https://i.imgur.com/QOnSvN8.png)

----
## 27. PROGRAM TO CALCULATE FACTORIAL OF A NUMBER WITH OR WITHOUT RECURSSION

### A. USING RECURSSION

      #include <stdio.h>
     long int multi(int n);
     int main()
    {
     int n;
    printf("Enter a positive integer: ");
    scanf("%d", &n);
    printf("Factorial of %d = %ld\n", n, multi(n));
    return 0;
      }
    long int multi(int n)
     {
      if (n >= 1)
        return n*multi(n-1);
    else
        return 1;
     }
*OUTPUT;*
![](https://i.imgur.com/URXJKGr.png)

### B. WITHOUT USING RECURSSION
    #include <stdio.h>
 
    int main()
    {
     int c, n, fact = 1;
 
     printf("Enter a number to calculate its factorial\n");
     scanf("%d", &n);
 
      for (c = 1; c <= n; c++)
    fact = fact * c;
 
     printf("Factorial of %d = %d\n", n, fact);
 
     return 0;
      }
*output;*
![](https://i.imgur.com/e0DeDOC.png)

----
## 28. PROGRAM TO FIND FIBONACCI SERIES WITH OR WITHOUT RECURSSION BOTH

### A. WITH RECURSSION
     #include<stdio.h>
 
    int Fibonacci(int);
 
    int main()
    {
      int n, i = 0, c;
    printf("Enter Number till you want the series:\n");
     scanf("%d",&n);
 
    printf("Fibonacci series\n");
 
     for ( c = 1 ; c <= n ; c++ )
    {
       printf("%d\n", Fibonacci(i));
      i++; 
    }
 
    return 0;
     }
 
    int Fibonacci(int n)
    {
     if ( n == 0 )
      return 0;
     else if ( n == 1 )
      return 1;
     else
      return ( Fibonacci(n-1) + Fibonacci(n-2) );
     }
*OUTPUT;*
![](https://i.imgur.com/foskvmM.png)

### B. WITHOUT RECURSSION

     #include<stdio.h>    
     int main()    
     {    
    int n1=0,n2=1,n3,i,number;    
     printf("Enter the number of elements:");    
     scanf("%d",&number);    
     printf("\n%d %d",n1,n2); 
     for(i=2;i<number;++i 
     {    
         n3=n1+n2;    
      printf(" %d",n3);    
       n1=n2;    
    n2=n3;    
     }  
     return 0;  
     }    
*OUTPUT;*
![](https://i.imgur.com/yGvPIb9.png)
     
----
## 29. PROGRAM TO CALCULATE AVERAGE OF FIVE NUMBERS USING FUCTION

    #include <stdio.h>
     float average(int a, int b, int c, int d, int e){
     return (float)(a+b+c+d+e)/5;
      }
    int main()
     {
      int num1, num2, num3, num4, num5;
    float avg;

    printf("Enter first number: ");
    scanf("%d",&num1);
    printf("Enter second number: ");
    scanf("%d",&num2);
     printf("Enter third number: ");
    scanf("%d",&num3);
      printf("Enter fourth number: ");
    scanf("%d",&num4);
    printf("Enter fifth number: ");
     scanf("%d",&num5);
    

    
    avg = average(num1, num2, num3, num4, num5);

                                                                               
    printf("Average of 5 numbers is: %.2f\n",avg);
    return 0;
     }        

*OUTPUT;*
![](https://i.imgur.com/NAFX4xF.png)

----
## 30.  PROGRAM TO IMPLEMENT LINEAR SEARCH AND BINARY SEARCH 

### A. LINEAR SEARCH
    #include <stdio.h>
  
    int main()
    {
    int array[100], search, c, n;
 
     printf("Enter number of elements in array\n");
     scanf("%d", &n);
 
      printf("Enter %d integer(s)\n", n);
   
      for (c = 0; c < n; c++)
    scanf("%d", &array[c]);
    
    printf("Enter a number to search\n");
    scanf("%d", &search);
 
      for (c = 0; c < n; c++)
     {
      if (array[c] == search)                                      
    {
      printf("%d is present at location %d.\n", search, c+1);
      break;
    }
     }
      if (c == n)
    printf("%d isn't present in the array.\n", search);
  
     return 0;
     }

*OUTPUT;*
![](https://i.imgur.com/2IiasLu.png)

### B. BINARY SEARCH
    #include <stdio.h>
 
     int main()
    {
     int c, first, last, middle, n, search, array[100];
 
    printf("Enter number of elements\n");
    scanf("%d",&n);
 
    printf("Enter %d integers\n", n);
 
    for (c = 0; c < n; c++)
       scanf("%d",&array[c]);
 
    printf("Enter value to find\n");
    scanf("%d", &search);
 
    first = 0;
    last = n - 1;
    middle = (first+last)/2;
 
    while (first <= last) {
       if (array[middle] < search)
         first = middle + 1;    
      else if (array[middle] == search) {
         printf("%d found at location %d.\n", search, middle+1);
         break;
      }
      else
         last = middle - 1;
 
      middle = (first + last)/2;
    }
     if (first > last)
       printf("Not found! %d isn't present in the list.\n", search);
 
     return 0;  
      }

*OUTPUT;*
![](https://i.imgur.com/WfPoaoc.png)

----
## 31. PROGRAM TO IMPLEMENT BUBBLE SORT
    #include <stdio.h>
 
    int main()
    {
     int array[100], n, c, d, swap;
 
     printf("Enter number of elements\n");
    scanf("%d", &n);
 
    printf("Enter %d integers\n", n);
 
    for (c = 0; c < n; c++)
    scanf("%d", &array[c]);
 
     for (c = 0 ; c < n - 1; c++)
     {
     for (d = 0 ; d < n - c - 1; d++)
    {
      if (array[d] > array[d+1]) 
      {
        swap       = array[d];
        array[d]   = array[d+1];
        array[d+1] = swap;
      }
    }
     }
 
     printf("Sorted list in ascending order:\n");
 
     for (c = 0; c < n; c++)
     printf("%d\n", array[c]);
 
     return 0;
      }
*OUTPUT;*
![](https://i.imgur.com/FZZRqoR.png)

----

## 32. PROGRAM FOR STUDENT INFORMATION USING ARRAY STRUCTURE
    #include <stdio.h>
     struct student
    {
    char name[50];
    int roll;
    float marks;
    } s[10];
    int main()
     {
    int i;
    printf("Enter information of students:\n");
    for(i=0; i<3; ++i)
    {
        s[i].roll = i+1;
        printf("\nFor roll number%d,\n",s[i].roll);
        printf("Enter name: ");
        scanf("%s",s[i].name);
        printf("Enter marks: ");
        scanf("%f",&s[i].marks);
        printf("\n");
    }
    printf("Displaying information:\n\n");
    for(i=0; i<3; ++i)
    {
        printf("\nRoll number: %d\n",i+1);
        printf("Name: ");
        puts(s[i].name);
        printf("Marks: %.1f",s[i].marks);
        printf("\n");
    }
    return 0;   
       }
*OUTPUT;*

![](https://i.imgur.com/bxILvRk.png)

----

## 33. PROGRAM TO COMPUTE TRANSPOSE OF MATRIX
     #include <stdio.h>

     int main()
    {
    int a[10][10], transpose[10][10], r, c, i, j;
    printf("Enter rows and columns of matrix: ");
    scanf("%d %d", &r, &c);
    printf("\nEnter elements of matrix:\n");
    for(i=0; i<r; ++i)
        for(j=0; j<c; ++j)
        {
            printf("Enter element a%d%d: ",i+1, j+1);
            scanf("%d", &a[i][j]);
        }
    printf("\nEntered Matrix: \n");
    for(i=0; i<r; ++i)
        for(j=0; j<c; ++j)
        {
            printf("%d  ", a[i][j]);
            if (j == c-1)
                printf("\n\n");
        }
    for(i=0; i<r; ++i)
        for(j=0; j<c; ++j)
        {
            transpose[j][i] = a[i][j];
        }
    printf("\nTranspose of Matrix:\n");
    for(i=0; i<c; ++i)
        {
            printf("%d  ",transpose[i][j]);
            if(j==r-1)
                printf("\n\n");
        }
    return 0;
     }
*OUTPUT;*
![](https://i.imgur.com/PFw6fkO.png)

----
## 34. PROGRAM TO PRINT THE ADDRESS OF VARIABLE USING POINTER

    #include <stdio.h>
    int main() {
     int b;
     int *pt;

     b = 10;
      pt = &b;

     printf("\n[&a ]:Address of B = %p\n", &b);
    return 0 ;
    }
*OUTPUT;*
![](https://i.imgur.com/7RMPaej.png)

----
## 35. PROGRAM TO ACCESS ARRAY USING POINTER
    #include <stdio.h>
    int main()
    { 
     int data[5], i;
     printf("Enter elements: ");
     for(i = 0; i < 5; ++i)
     scanf("%d", data + i);
     printf("You entered: \n");
     for(i = 0; i < 5; ++i)
      printf("%d\n", *(data + i));
    return 0;
     }

*OUTPUT;*

![](https://i.imgur.com/y4gnHkE.png)       
       
